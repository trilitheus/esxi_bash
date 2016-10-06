Small collection of scripts to help with managing ESXi and VMs

    Usage: vm_command [-u esxi_username] [-h esxi_hostname] [-i ssh_key_file] [-a action] [-d datastore] [-b build] [-o clone_dir ] [-v]
    
    -u esxi_username : specify the username to connect to esxi with
    -h esxi_hostname : specify the esxi host
    -i ssh_key_file  : The ssh private key used to log into the esxi server
    -a action        : The action to perform (currently poweron, poweroff, registervm, unregistervm, clonevm, getstate, getip)
    -d datastore     : datastore containing the VM we are acting upon
    -b build         : the pipeline build number
    -o clone_dir     : the directory to clone to for clonevm actions
    -v               : be more verbose
