# easy-build-aosp-cn
Vagrantfile包含一个已配置好的ubuntu docker环境，虚拟机硬盘为1t,虚拟内存为12GB, 物理内存为4gb,以及docker的镜像源修改为国内。通过此环境可以在硬件配置受限的环境下[可分给虚拟机的内存不少于4GB]方便的使用虚拟机编译 [史上最简单Android源码编译环境搭建方法](https://zhuanlan.zhihu.com/p/24633328)的内容。

### usage

```bash

# in host
git clone --recurse-submodules https://github.com/andr0xfe/easy-build-aosp-cn
cd easy-build-aosp-cn
vagrant up && vagrant ssh

#in guest ssh
export AOSP_VOL=/vagrant/AOSP
cd /vagrant/docker-aosp/tests
bash ./build-*.sh
```

### dependents
[vagrant](https://www.vagrantup.com/)  
[virtualbox](https://www.virtualbox.org/)


<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>



### 感谢

[史上最简单Android源码编译环境搭建方法](https://zhuanlan.zhihu.com/p/24633328)

