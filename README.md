# debug-that-yaml

1. Create a GKE cluster (3 nodes, Standard, without Workload Identity)
2. `kubectl create namespace hello` 
3. `kubectl apply -f deployment.yaml` 
4. `kubectl apply -f service.yaml` 


I see this error: 

```
curl: (7) Failed to connect to 35.194.7.3 port 80: Connection refused
```
