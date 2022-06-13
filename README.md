# Ansible playbook to deploy simple python webapp to a minikube cluster

minikube driver used is docker, but it could be virtualbox.

Requires:
* docker engine to run the minikube node
* minikube installed
* kubectl installed
* ansible
* ansible-galaxy collection install community.kubernetes
* ansible-galaxy collection install cloud.common
