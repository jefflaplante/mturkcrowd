# NGINX for MTC

## Create a configmap for the NGINX configmap

``` bash
kubectl create configmap mtc-nginx --from-file=default.conf
```
