1) k3d cluster create mycluster --servers 1 --agents 2 --port 8081:30000@loadbalancer --port 8090:30001@loadbalancer


2) kubectl apply -f deployment.yaml

3) Acessar no host - localhost:8090
