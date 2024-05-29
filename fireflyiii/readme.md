
# MANUAL IMPORT Process

* Copy all  .csv files to ./_ffiii-import folder
* Rename the same as its .json file
* Run this command
* 
```
sudo docker exec -it fireflyiii-data-importer php artisan importer:auto-import /import
```

or within portainer
```
php artisan importer:auto-import /import
```
