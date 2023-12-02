
cd ~/dev/devenv/ansible

ansible-playbook --extra-vars @config/vars.yaml -i ansible_hosts k8s-ecosystem-only-playbook.yaml
