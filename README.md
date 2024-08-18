
### Some Words
This playbook will install kubernetes cluster in cidr `10.244.0.0/16` 

The configuration can be changed in hosts.ini file where you can add the desirable nodes for cluster

We will be using the `cilium` as cni and `containerd` as container runtime

### Prereq:
- You have to ensure ssh password less login by allowing password authentication in `/etc/sshd/sshd_config`
You can check the script for this @ `https://github.com/jamesii-b/os-configs/blob/main/rootbash`

