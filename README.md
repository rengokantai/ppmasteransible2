# ppmasteransible2
```
-
  tasks:
    - name:
      wait_for:
        port: 80
```
```
ansible centos3 -m service -a 'name=nginx state=stopped'
```
check doc
```
ansible-doc wait_for
```
