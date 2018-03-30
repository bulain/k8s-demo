# 安装minikube-windows-amd64.exe,重命名为minikube.exe
http://kubernetes.oss-cn-hangzhou.aliyuncs.com/minikube/releases/v0.25.0/minikube-windows-amd64.exe
# 安装virtualbox
# 安装kubectl
# 以上都添加到系统path路径

# minikube start --registry-mirror=https://xxxxxxxx.mirror.aliyuncs.com
# minikube stop
# minikube addons enable ingress

# kubectl run nginx --image=nginx
# kubectl expose deployment nginx --type=NodePort --port=80
# kubectl delete service nginx
# kubectl delete deployment nginx

# kubectl get deploy
# kubectl get po
# kubectl get svc
# kubectl get ep
# kubectl get sts

# kubectl create -f nginx.yaml
# kubectl create -f tomcat.yaml
# kubectl create -f mysql.yaml

# helm init --upgrade -i registry.cn-hangzhou.aliyuncs.com/google_containers/tiller:v2.8.0 --stable-repo-url https://kubernetes.oss-cn-hangzhou.aliyuncs.com/charts

