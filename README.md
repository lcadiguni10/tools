> **_Disclaimer_** :  
> Those scripts are ubuntu and fedora in 24.04 and 41 respective
___

## Prepare Workstation

1. Install Ansible
```bash
sudo apt update && sudo apt install ansible unzip git -y
or
sudo dnf update && sudo dnf install ansible unzip git -y
```
2. Clone this repository
```bash
git clone https://github.com/caiodelgadonew/tools.git
```

3. Apply the configuration
```bash
ansible-playbook tools/ubuntu.yml --ask-become-pass
or
ansible-playbook tools/fedora.yml --ask-become-pass
