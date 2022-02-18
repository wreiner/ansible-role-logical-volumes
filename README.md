# Ansible Role: logical-volumes

Creates filesystems and mounts

## Mandatory Role Variables

To create logical volumes define them in an array like the following:

```
logical_volumes__lvconfig:
  - lv_name: iso_base_lv
    vg: root_vg
    size: 256M
  - lv_name: vmpool01_lv
    vg: root_vg
    size: 256M
```

## Optional Role Variables

None.