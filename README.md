# talos-openstack

## Getting started

- Configure your Openstack Access [Link](https://docs.openstack.org/python-openstackclient/latest/configuration/index.html)
- Install talosctl [Link](https://www.talos.dev/v1.9/talos-guides/install/talosctl/)
- Install kubectl [Link](https://kubernetes.io/docs/tasks/tools/)
- Install ansible [Link](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

## Deploy Talos Cluster in Openstack

This Playbook Deploys a K8s Cluster in a private Network with 3 Control Planes and 3 Worker 
The Talos API and Kube API are behind a Loadbalancer
Your talosconfig and kubeconfig will be in $HOME/talos

Run `ansible-playbook site.yml`

Happy Hacking
