# Zsh shell Ansible script.

Installs ZSH, oh-my-zsh and powerlevel10k plugin.

## Configure


* Set your username in `zsh_user` variable in (vars/vars.yml)[vars/vars.yml].

* Set the name/IP of the server in `hosts` file.


## Run

```
ansible-playbook -T playbook.yml
```

