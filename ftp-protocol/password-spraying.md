# Password spraying

### Password spraying (without bruteforce)

```bash
nxc ftp 192.168.1.0/24 -u userfile -p passwordfile --no-bruteforce
```

By default nxc will exit after a successful login is found. Using the `--continue-on-success` flag will continue spraying even after a valid password is found. Usefull for spraying a single password against a large user list.
