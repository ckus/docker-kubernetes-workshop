# Setup de ambiente de trabajo

Pasos a seguir para el correcto funcionamiento de Docker y Kubernetes localmente en tu computador.

1. Clona este repositorio a tu computador 
```
git clone  https://github.com/ckus/docker-kubernetes-workshop.git
```
2. Instala Docker ([Mac](https://docs.docker.com/docker-for-mac/install/) /[Windows](https://docs.docker.com/docker-for-windows/install/)) (Para Linux depende de la distribución, no voy a listarlas ya que pueden ser mucho, lo único que hay que hacer es buscar "install docker on linux" ;) y seguir los pasos según la distribución)
3. Testear Docker
   Abrir una ventana de Terminal (commando prompt o powershell en windows)
```
docker ps
docker images
```
4. Instalar Kubernetes localmente con [Minikube](https://github.com/kubernetes/minikube) (Docker viene con la posiblidad de crear un cluster de Kubernetes, pero no tiene todas las capacidades de K8s, es convenientes utilizarlo para testeos de aplicaciones simples)
5. Testear Kubernetes
   Abrir un ventana de Terminal (commando prompt o powershell en windows)
```
kubectl get nodes
kubectl get namespces
```
6. Ya somos felices con Docker y Kubernetes en nuestro computador, ahora a jugar!  