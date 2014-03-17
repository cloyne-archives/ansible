# cloyne ansible automation

contains automation for
- file server
- desktop computer(s)

## how to install

```
git clone git@github.com:cloyne/ansible.git
cd ansible
```

## how to install fileserver

on the server (files.cloyne.net),

```
aptitude install python-pycurl
```

on your laptop / desktop,
```
ansible-playbook -i production fileservers.yml -K -k
```
