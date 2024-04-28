# Kubernets + python

### Comandos utilizados

Clonando o repositorio

```
git clone https://github.com/otavioliraneves/Kubernetes-Python.git
``` 

1. Implantando o Script no Cluster
``` 
kubectl apply -f deployment.yaml
``` 

2. Verifique o status da implantação usando o comando **kubectl**
3. 
``` 
microk8s kubectl get pods
``` 

3. Coletar Logs do Pod
``` 
microk8s kubectl logs <pod_name> -n default
``` 

4. Obtendo informações de recursos do Cluster de kubernetes
``` 
kubectl get all
``` 

###Logs do pod

![Tux, the Linux mascot](/assets/images/cluster-comandos-utilizados.png)

###Informações da implantação

![Tux, the Linux mascot](/assets/images/cluster-informacoes-implatancao.png)

# Conclusão

Este guia fornece um roteiro detalhado para executar um script Python em um cluster Kubernetes. Seguindo estas etapas, você poderá implantar e executar seus scripts Python em um ambiente Kubernetes de forma eficiente.

