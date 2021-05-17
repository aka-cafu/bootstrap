# Pacman packages

To insert new packages, update packages versions or user/groups options modify them in [vars/main.yml](./vars/main.yml)

```
user: felipe
group: docker,vboxusers
home_bin: /usr/local/bin
packages:
  - package
  - new_package
  - other_package
  - another_package
# k8s tools #  
helm_version: 3.6.1 <=== update version
kubectl_version: 1.22.0 <=== update version
# hashicorp tools # 
tf_version: 1.0 <=== update version
packer_version: 1.7.2
vagrant_version: 2.2.15
```