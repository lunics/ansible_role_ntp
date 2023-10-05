# Ansible role: NTP

Role to setup Chrony or NTP.

Only tested on Archlinux.

## Usage
Override the [defaults](https://github.com/lunics/ansible_role_ntp/blob/main/defaults/main.yml)
```yaml
ntp_daemon:  chrony     # chrony or ntp
time_format: UTC        # UTC or localtime

ntp_servers:
  - 0.pool.ntp.org
  - 1.pool.ntp.org
  - 2.pool.ntp.org
  - 3.pool.ntp.org
```
