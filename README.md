# ansible-role-libvirt-vm
add packer prebuild virtual machines to libvirt


for ssh connections add the following to your ~/.ssh/config
```
Host 192.168.122.*
  User ansibleRoot
  ProxyCommand ssh -a -q srv03 nc %h 22
  StrictHostKeyChecking no
```
