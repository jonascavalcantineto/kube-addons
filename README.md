# Install Kube Addons
These Addons only install after kubernetes cluster on.

# 1. Install kube-dns.yml
```
kubectl apply -f kube-dns.yml
```
# 2. heapster modules
# 2.1. Install influxdb.yaml
```
kubectl apply -f influxdb.yaml
```
# 2.2. Install grafana.yaml
```
kubectl apply -f grafana.yaml
```
# 2.3. Install heapster.yaml
```
kubectl apply -f heapster.yaml
```
# 3. Install kubernetes-dashboard.yaml
```
kubectl apply -f kubernetes-dashboard.yaml
```