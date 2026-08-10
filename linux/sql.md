### to see if postgresql is installed
dpkg -l | grep postgresql


## Managing the service
sudo systemctl start postgresql
sudo systemctl stop postgresql
sudo systemctl status postgresql
----> press ```q``` if you want to exit
sudo systemctl restart postgresql

sudo systemctl enable postgresql
sudo systemctl disable postgresql


## sql commands for linux
```
sudo -i -u postgres
psql
```

```\q``` => quits psql entirely and drops you back to your terminal (still logged in as the postgres)

to exit postgres and go back to normal terminal, use this command:  ```exit```









