# kuber_cloud
Комманды проверки кластера
kubectl get nodes;
kubectl get pods --all-namespaces;
kubectl get services;
kubectl cluster-info;
kubectl api-versions;
kubectl config view;
kubectl cluster-info dump;
cat /etc/containerd/config.toml;
kubectl get pod;
kubectl apply -f replicaset.yaml;
kubectl get replicaset;
kubectl edit replicaset my-replicaset;
kubectl describe replicaset my-replicaset;
kubectl describe pod -n kube-system calico-node-lt82b;
kubectl set image replicaset my-replicaset nginx=nginx:1.13;
kubectl delete all --all;
kubectl get deployments.apps;
kubectl edit deployments.apps my-deployment;
kubectl rollout undo deployment my-deployment --to-revision=0 на прошлую версию, 1 на позапрошлую;
![Снимок экрана от 2025-01-07 03-10-00](https://github.com/user-attachments/assets/0639b3a1-7ae7-43b2-b322-5a987cd9006e)
![Снимок экрана от 2025-01-07 01-48-14](https://github.com/user-attachments/assets/257f4680-04d0-4a02-9e33-52694af0306e)
![Снимок экрана от 2025-04-29 23-19-58](https://github.com/user-attachments/assets/0c8c6e55-f938-4b81-a60d-2104ee634943)
