# How to run Hugo to create our docs

* See the wiki for more details

## Interactive run
```
.\hugo server --config ..\customer-portal\config-customer.yaml
.\hugo server --config ..\account-portal\config-account.yaml
.\hugo server --config ..\enterprise-portal\config-enterprise.yaml
.\hugo server --config ..\api\config-api.yaml

```

## Run to output for upload to blobstore
```
.\hugo --config ..\customer-portal\config-customer.yaml --baseUrl https://docs.xarios.cloud --destination public  
```