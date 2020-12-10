# akarzazi/netbox

Small Docker toolbox for troubleshooting.

Includes basic tools like:
- nc
- curl
- dig
- nslookup
- ping
- vi

## Use

With Docker

```bash
docker run -it akarzazi/netbox
```

With Kubernetes

```bash
kubectl apply -f https://raw.githubusercontent.com/akarzazi/netbox/main/k8s/as-pod.yml

kubectl exec -it netbox -- /bin/bash
```

## Images

View docker hub https://hub.docker.com/r/akarzazi/netbox

Tags | Dockerfile | OS Version | size
-----------| -------------| -------------|----
alpine, latest | [Dockerfile](https://github.com/akarzazi/netbox/blob/main/alpine/Dockerfile) | Alpine 3.12 | 22 MB
ubuntu | [Dockerfile](https://github.com/akarzazi/netbox/blob/main/ubuntu/Dockerfile) | Ubuntu 20.10| 180 MB


