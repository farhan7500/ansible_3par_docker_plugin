# ansible_3par_docker_plugin

Ansible playbooks to install the HPE 3PAR Docker Volume plugin for use with Kubernetes/OpenShift environments

Requirements:

  - login to 3PAR to create known_hosts file
  - modify files/hpe.conf based on your environment configuration
  - modify hosts file to match your cluster setup

Run
```
$ ansible-playbook -i hosts install_hpe_3par_volume_driver.yml
```

Known-issues:
  - playbook hangs on starting doryd but can start manually


