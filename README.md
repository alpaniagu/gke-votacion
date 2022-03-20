### Ejemplo de la aplicación de votos para GKE

Basada en la original [example-voting-app](https://github.com/dockersamples/example-voting-app) de los ejemplos de Docker(https://github.com/dockersamples) modificada para que funcione mejor en GKE

![Architecture diagram](https://github.com/dockersamples/example-voting-app/raw/master/architecture.png)

Kubernetes Services : Type   
db  : ClusterIP      
redis   : ClusterIP    
result-service  :  LoadBalancer    
voting-service   :  LoadBalancer    

```
kubectl create -f .
```
