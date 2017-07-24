# oic-IP-Tables

@Fabrice ajoutera les reglès de pare-feu. Bloquer tout accès sur les IP publiques des machines hots


> Change Ambari admin password

```sh
1. Log on to ambari server host shell

2. Run 'psql -U ambari-server ambari'

3. Enter password 'bigdata'

4. In psql:

update ambari.users set user_password='538916f8943ec225d97a9a86a2c6ec0818c1cd400e09e03b660fdaaec4af29ddbb6f2b1033b81b00' where user_name='admin'

5. Quit psql

6. Run 'ambari-server restart'

This will reset the admin account back to the password of 'admin'
``` 

