# ansible-vcenter-manage
Sample playbook to manage actions via a vCenter API

Edit env_data.yml with your environment information, then call the playbook as such:

```
# ansible-playbook -i inventory/ manage-esx-hosts-single-playbook.yml -e @env_data.yml
```

To call the playbook that uses the role, use:
```
# ansible-playbook -i inventory/ manage-esx-hosts-role.yml -e @env_data.yml
```
