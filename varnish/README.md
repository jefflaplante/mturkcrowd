# Varnish for MTC

## Create a configmap for the varnish configmap

``` bash
kubectl create configmap mtc-varnish --from-file=default.vcl
```
