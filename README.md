# Vault playbook

It is a playbook to deploy Hashicorp Vault cluster. Now it has many cons and problems with structure and security, but later on it is going to be much improved. I am planning to make it universal for different backends. Now only raft backend is available!

# How to start
`pip install -r requirements.txt`

`ansible-playbook -i hosts-sample.yaml main.yaml --ask-vault-pass`

