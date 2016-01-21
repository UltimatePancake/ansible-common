# common

## Usage

```yaml
roles:
  - common
```

## Notes

Default packages can be defined via host_Vars or group_vars

```yaml
# $ANSIBLE_ROOT/group_vars/all
# $ANSIBLE_ROOT/group_vars/groupname
# $ANSIBLE_ROOT/host_Vars/hostname

common_packages:
  - vim
  - unzip
```

Extra packages can be defined via host_vars or group_vars

```yaml
# $ANSIBLE_ROOT/host_vars/hostname

extra_packages:
  - python
  - ruby
  - whatever_you_want
```
