# Ansible-Docker-Swarm
Repo to deploy a docker swarm with ansible on AWS

# Machine Types
This Ansible is based on Docker running on Ubuntu Machines (ami: 7c412f13)

# Topology
There are 3 Swarm Master Nodes and 3 Swarm Worker Nodes

# Key Pairs
This Ansible script uses ssh keypairs to connect on remote machines.
It assumes that you've already copied the .pub key to the Swarm machines and uses the .priv key located on keypairs/ to connect.
If you are willing to use SSH user and password, is needed to change the connection on inventories/hosts