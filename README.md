# TIOXY - Ansible setup
My first-setup-as-code
Only supported distro is **Antergos**(Arch based) at the moment.
<br/>
**.bashrc** file is located at [http://bashrc.tioxy.com](http://bashrc.tioxy.com)


## Installation

#### Antergos
- Make sure that you have Ansible and Git installed
```sh
sudo pacman -S ansible git
```

- Clone the repository and run the ansible playbook
```sh
ansible-playbook --ask-sudo-pass -i hosts master.yml
```
