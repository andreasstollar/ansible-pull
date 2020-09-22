# ansible-pull
An collection of playbooks written to run using ansible-pull

## Procedure
Add this to /etc/ansible/hosts

```
[localhost]
127.0.0.1
```

Run ansible on remote host like so

```
# ansible-pull -Uhttps://github.com/andreasstollar/ansible-pull.git linux_upgrade.yaml
```

