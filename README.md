# ibm-ssh

create a pod for ssh:
```bash
kubectl apply -f https://github.com/ShubhamTatvamasi/ibm-ssh/raw/master/ssh.yaml
```

ssh to host machine:
```bash
kubectl exec -it -n ibm-system ssh -- ssh localhost
```

check logs:
```bash
kubectl logs -n ibm-system ssh -f
```
