# useful-Script

1.) To list all the registered VMs                             -----> vboxmanage list vms
2.) To start a VM,                                             -----> vboxmanage startvm (name or UUID)
3.) VM is running, you’ll switch                               -----> vboxmanage controlvm (subcommand) (VM state operations include pause, resume, reset, poweroff, and savestate.)
4.) To unregister (remove) a stopped VM                        -----> vboxmanage unregister (name or UUID) --delete
5.) To view the information about a VM                         -----> vboxmanage showvminfo (name or UUID)
6.) To change a VM’s description,                              -----> vboxmanage modifyvm (name or UUID) --description <new description>
7.) To change the amount of RAM assigned to a VM               -----> vboxmanage modifyvm (name or UUID) --memory <RAM in MB>
8.) To change the number of virtual CPUs assigned to a VM      -----> vboxmanage modifyvm (name or UUID) --cpus <number>

9.) (For running machine) 
To restore the connection                                  -----> vboxmanage controlvm (name or UUID) setlinkstate1 on|off

