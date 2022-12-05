## Slurmify
This will run on a set of VMs to create a Slurm cluster.

### Tasks:
-  Copy a common slurm.conf file
-  Update /etc/hosts with the names and IPs of the VMs
-  Update /etc/slurm/nodes.conf with the names and CPU layout of the VMs
-  Verify certain packages are installed
-  Verify the login host/slurm controller is configured correctly
-  Start slurm services on all VMs
