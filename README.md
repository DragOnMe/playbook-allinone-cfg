# playbook-allinone-cfg
Ansible playbook inventory configuration files for installing OpenShift 3(origin version, release 1.4.1) on CentOS 7.3
 * Containrized installation
 * Single node all-in-one installation
 * 3-node installation
 * pv.json for Persistent Volume Reclaimation

# How to use
Pre-requisites
 * Prepare and setup 3 CentOS 7.x servers and 1 DNS server
 * Install related softwares and NFS volumes
 * run: git clone https://github.com/DragOnMe/openshift-ansible.git
 * run: git clone https://github.com/DragOnMe/playbook-allinone-cfg.git
 * and run: ansible-playbook -i ./playbook-allinone-cfg/centos7-3node-playbook.cfg ./openshift-ansible/playbooks/byo/config.yml

# Refer to
http://bryan.wiki/273

# Good Luck

  - Barracuda
