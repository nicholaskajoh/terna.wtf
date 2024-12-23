# Playbooks
- Create `hosts` file from `hosts.example`.

- Set env vars:
    ```sh
    export ANSIBLE_HOST_KEY_CHECKING=False
    export ANSIBLE_REMOTE_TMP=/tmp/ansible
    ```

## Update Debian hosts
```sh
ansible-playbook ./playbooks/update-debian-hosts.yaml -i ./inventory/hosts
```
