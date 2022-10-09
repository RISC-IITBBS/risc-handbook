# Installation

## Setting up Operating System

[Ubuntu 22.04](https://ubuntu.com/download/desktop) is recommended for ROS if you already have Ubuntu 20.04, that is also fine although for versions older than this we recommend upgrading to 22.04.

For those who currently have **Windows** as the only OS on their machine, the best way to start using Ubuntu would be to **dual boot**. Here is a guide on how to do [this](https://itsfoss.com/install-ubuntu-1404-dual-boot-mode-windows-8-81-uefi/) or you can go through this Youtube [video](https://www.youtube.com/watch?v=-iSAyiicyQY) . For **MacOS** users, dual booting is an  [option](https://youtu.be/CNk-ftc-qRI) but it is recommend to use a virtual machine.

If you are unable to dual boot for any reason, you can try setting up a **virtual machine**. The first step in this is to install a virtualisation software. For Windows you can use either [VirtualBox](https://www.virtualbox.org/) (free) or Vmware Workstation and for MacOS either [VirtualBox](https://www.virtualbox.org/) (free),
Vmware Fusion or Parallels. After getting one of the above, follow the instructions given [here](https://ethz.ch/content/dam/ethz/special-interest/mavt/robotics-n-intelligent-systems/rsl-dam/ROS2020/CoursePreparation.pdf) (skip ahead to the *Download Image* section). After completing the given procedure you will be equipped with all the basic tools required for Robotics including ROS,catkin and git.

In the unfortunate case that the **above options do not work**, for Windows users there is still a way - [WSL](https://ubuntu.com/wsl). Do be warned however, this path is fraught with frustration and much debugging. Only continue if you have exhausted other options. For a guide on setting up WSL for ROS, look [here](https://janbernloehr.de/2017/06/10/ros-windows). 

For those whom none of the above are possible, consider using the online browser based [ROS Development Studio](https://www.theconstructsim.com/). Keep in mind that it has a limited access time per week and performance may be questionable.

## Installing Robot Operating System (ROS)

**For Ubuntu 22.04 users** :  [ROS Humble Hawksbill](https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html)     
**For Ubuntu 20.04 users** :  [ROS Noetic](http://wiki.ros.org/noetic/Installation/Ubuntu)


* **Code Editors** : [VSCode](https://code.visualstudio.com/) is recommended for boosting productivity​ which has plugins for python and ROS. A comprehensive guide for how to integrate ROS into your favourite IDE can be found [​here](http://wiki.ros.org/IDEs)​.

  
* For installing developed ROS packages replace <package_name> with name of the ROS package.

```bash
	sudo apt install ros-$ROS_DISTRO-<package_name>
```

* Because of having conflicting python path Anaconda and ROS can't be used in same. For dealing with this edit your
.bashrc  file by commenting the anaconda python path like this

```bash
	//  export PATH="/home//anaconda3/bin:$PATH "
```

* It is recommended to source the workspace on startup by editing your .bashrc file by including following line. Replace <workspace_path> with the path of your workspace

```bash
	source <workspace_path>/devel/setup.bash
```

Note : Two workspaces can't be sourced at the same time.



