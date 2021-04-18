# Insight
During the kubernetes cluster setup, there are a lot prerequisites that needs to be done in master as well as worker servers. This is an Ansible playbook to complete the initial setup in both master and worker servers.

Tasks completed in the playbook
- Repo update
- Disable swap
- Remove the swap entry in fstab
- Install docker and curl
- Install GPG keys for kubernetes
- Add kubernetes repositories to the system
- Install kubeadm, kubectl and kubelet

# Usage
Clone the repo, update the hosts and execute.
