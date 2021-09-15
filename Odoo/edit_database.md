```
# 1 step 
sudo -i -u postgres
psql
\l # show database
\c DDATELIER


service postgresql status
SELECT * FROM tms_gasoil_order ORDER BY ID DESC LIMIT 22;
SELECT id,create_date,date,liter FROM tms_gasoil_order ORDER BY ID DESC LIMIT 21;
DELETE FROM tms_gasoil_order WHERE ID ==77501; 
```
