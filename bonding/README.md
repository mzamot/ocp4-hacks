# Add Host playbook 

This playbook creates the MachineConfig (mc) file for bonding/LACP.  
It should be included inside ${CLUSTERNAME}/openshift as a manifest or created post-deployment.

To use it, add the details in `group_vars/all.yaml` and run the playbook as:

```
ansible-playbook main.yaml
```
