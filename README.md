# kubernetes

minikube install on ubuntu


 
     sudo apt-get update -y
     
      curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
      sudo install minikube-linux-amd64 /usr/local/bin/minikube && rm minikube-linux-amd64
      minikube start
      minikube start --driver=docker
      sudo apt install docker.io -y
      minikube start
      kubectl get po -A
      sudo snap install kubectl --classic
      kubectl get po -A
      
