# selenoid4k8s kubernetes deployment

# Depoyment using helm <a name="helm"></a>
```
helm install --name browser-hub selenoid4k8s/

http://node01:30001/
http://node01:30002/
```

For access via cloud LoadBalancer
```
helm install --name certa-browser-hub selenoid4k8s/ --set service.type=LoadBalancer

http://LoadBalancerIP:4444/
http://LoadBalancerIP:8080/
```
