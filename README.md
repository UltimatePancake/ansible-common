# dg_common

## Usage

```yaml
roles:
  - dg_common
```

## Notes

Extra packages can be defined per host via host_vars

```yaml
# $ANSIBLE_ROOT/host_vars/hostname

host_packages:
  - python
  - ruby
  - whatever_you_want
```
