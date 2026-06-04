# Ansible Config for Pis Terminals to present Home Assistant Dashboards


# WIP notes

  * To make Ansible work with password protected SSH keys, edit ~/.ssh/config to contain
    ```
    Host *
       AddKeysToAgent yes
    ```
   Make sure that ssh-agent is running, then connecting
  * Add all SSH publiy keys for all hosts in the inventory to ~/.ssh/config
