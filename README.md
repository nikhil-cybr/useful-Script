# useful-Script

To list all the registered VMs                             -----> vboxmanage list vms
To start a VM,                                             -----> vboxmanage startvm <name or UUID>
VM is running, you’ll switch                               -----> vboxmanage controlvm <subcommand>    (VM state operations include pause, resume, reset, poweroff, and savestate.)
To unregister (remove) a stopped VM                        -----> vboxmanage unregister <name or UUID>  --delete
To view the information about a VM                         -----> vboxmanage showvminfo <name or UUID>
To change a VM’s description,                              -----> vboxmanage modifyvm <name or UUID> --description <new description>
To change the amount of RAM assigned to a VM               -----> vboxmanage modifyvm <name or UUID> --memory <RAM in MB>
To change the number of virtual CPUs assigned to a VM      -----> vboxmanage modifyvm <name or UUID> --cpus <number>

(For running machine) 
To restore the connection                                  -----> vboxmanage controlvm <name or UUID> setlinkstate1 on|off
