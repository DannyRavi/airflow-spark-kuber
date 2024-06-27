please follow thos readme:
for create namespaces

```sh
kubectl create namespace airflow
```

for run cluster

```sh
kubectl apply -f . -n airflow
```

wait untill all image pull process going done. we can check pods states with bellow command:

```sh
kubectl get pods -n airflow
```

if all pods status are Running and pv/pvc are created


