ckanext-scheming
================

ckanext-scheming for Skeena Salmon Data Centre

Installation
================

To install: 
```
sudo docker exec -it ckan bash #to go into the ckan container
cd ./src
git clone https://github.com/skeenatrust/ckanext-scheming.git
```

Add to production.ini:
```
ckan.plugins = scheming_datasets
    
## Scheming Settings                                                       
## module-path:file to schemas being used                                
scheming.dataset_schemas = ckanext.scheming:ckan_dataset.yaml
```

Restart CKAN:
```
sudo docker-compose restart ckan
```

    



