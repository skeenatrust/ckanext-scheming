ckanext-scheming
================

ckanext-scheming for Skeena Salmon Data Centre

Installation
================

Add to production.ini:

    ckan.plugins = scheming_datasets
    
    ## Scheming setting                                                       
    ## module-path:file to schemas being used                                
    scheming.dataset_schemas = ckanext.scheming:ckan_dataset.yaml




