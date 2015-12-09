# Easy linux on your laptop

## Download and install
[http://download.virtualbox.org/virtualbox/5.0.10/VirtualBox-5.0.10-104061-OSX.dmg](http://download.virtualbox.org/virtualbox/5.0.10/VirtualBox-5.0.10-104061-OSX.dmg)

[https://releases.hashicorp.com/vagrant/1.7.4/vagrant_1.7.4.dmg](https://releases.hashicorp.com/vagrant/1.7.4/vagrant_1.7.4.dmg)

[https://opscode-omnibus-packages.s3.amazonaws.com/mac_os_x/10.10/x86_64/chefdk-0.10.0-1.dmg](https://opscode-omnibus-packages.s3.amazonaws.com/mac_os_x/10.10/x86_64/chefdk-0.10.0-1.dmg)

## Open Terminal on your mac and type the following

### cd to your home directory
`cd`

### create a cookbook to run linux
`chef generate cookbook linux`

### cd into cookbook
`cd linux`

### list available linux machines
`kitchen list`

### converge ubuntu machine
`kitchen converge ubuntu`

### login to ubuntu machine
`kitchen login ubuntu`

### run random commands on ubuntu machine
```
cd 
pwd
ls
ls -la
whoami
time
```

### exit ubuntu machine
`exit`

### destroy ubuntu machine
`kitchen destroy`
