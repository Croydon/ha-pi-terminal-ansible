# Ansible Config for Pis Terminals to present Home Assistant Dashboards


## Terminal Notes

### Manual initalizing

  * Install Raspberry Pi OS
  * Put public SSH key to `/root/.ssh/authorized_keys`
  * Edit `etc/ssh/sshd_config` to contain `PermitRootLogin prohibit-password` and `PubkeyAuthentication yes`
