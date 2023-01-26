# AWS Workshop

Repo is used for hosting studying respources. Everythin you find here is meant to be used for educational purposes only.

## Lab VM Setup

LabVM is a Linux (Ubuntu 20 LTS) virtual machine with some services and packages pre-installed. It can be used as a playground for various purposes. It is developed and tested for VirtualBox running on Windows 10. Other providers or versions of Windows might also work, but were not verified. It is provisioned with Vagrant and configured with Ansible.

### Install Pre Requisite packages.

1. VirtualBox 

    [Download VirtualBox from their official site](https://download.virtualbox.org/virtualbox/7.0.4/VirtualBox-7.0.4-154605-Win.exe) and install it.

    NOTE: [Microsoft Visal C++ Redistributalble](https://aka.ms/vs/17/release/vc_redist.x64.exe) is required.

 2. Vagrant

    [Download Vagrant installer](https://releases.hashicorp.com/vagrant/2.3.4/vagrant_2.3.4_windows_amd64.msi) from the [official site](https://developer.hashicorp.com/vagrant/downloads) and instll it.

### Provision the VM
Once all pre-requisite software is installed, just cd to the LabVM folder and run:
```
vagrant up
```
And wait for the provissioning to complete.

### Access the VM

#### vagrant ssh

Vagrant has a built-in mechanism of establishing an ssh session to the provisioned VM. To connect, cd into the LabVM folder and run:
```
vagrant ssh
```

#### Setup your favorite SSH client


While in the LavVM directory run the following command:

```
vagrant ssh-config
```


[PuttyGen](https://the.earth.li/~sgtatham/putty/latest/w64/puttygen.exe) 

Open key file
Navigate to [Key] -> [Parameters for saving key files...]

Make sure PPK file version is set to 2


 docker run -p 8080:8080 -d nginxdemos/nginx-hello


 