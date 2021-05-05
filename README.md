## my workstation setup

```
this repository contains the my setup configurations that I use in my daily routine
```

### installation


to run the playbook, first you need to install **ansible** and **git**

```bash
$ pacman -S ansible git
```
then clone this repository

```bash
$ git clone https://github.com/aka-cafu/bootstrap.git
```
```bash
$ cd bootstrap && \
    ansible-playbook playbook.yml --connection=local --ask-become-pass
```