# ansible-general
---
Required Environment Variables:  
- OPT_INVENTORY
- OPT_HOSTS
- OPT_HOME
- OPT_MYSQL_DATA_DIR
- OPT_DATABASE_NAME
- OPT_TABLE_NAME
- OPT_REPLICAS
- OPT_IDLE_INTERVAL


Example:  
```
ansible-playbook -i $OPT_INVENTORY --extra-vars="OPT_HOSTS=$OPT_HOSTS" connection-test.yml
```