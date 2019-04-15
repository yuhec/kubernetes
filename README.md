# kubernetes
### Install
ansible-playbook plays/k8s-setup.yml --ask-pass --extra-vars "ansible_become_pass=Laetitia1998."
### Test
ssh laetitia@40.89.156.250
sudo -i
kuberctl get nodes