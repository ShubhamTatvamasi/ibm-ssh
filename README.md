# ibm-ssh

create a pod for ssh
```bash
kubectl apply -f https://raw.githubusercontent.com/ShubhamTatvamasi/ibm-ssh/master/ssh.yaml
```

ssh to host machine
```bash
kubectl exec -it -n ibm-system ssh -- ssh localhost
```
