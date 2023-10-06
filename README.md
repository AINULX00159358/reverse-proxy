# Nginx Reverse Proxy

This Repo provides manifests for deploying Nginx Service and ConfigMap for the Configuration


# Deployment
```
git clone https://github.com/AINULX00159358/reverse-proxy.git 
```
``` cd reverse-proxy ```

```
kubectl create configmap nginx-config --from-file=nginx-conf
```

```
kubectl apply -f nginx-service
```
