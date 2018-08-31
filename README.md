# kube-proxy

github addr [https://github.com/kubernets/kube-proxy](https://github.com/kubernets/kube-proxy)

docker hub addr [https://hub.docker.com/u/kubernets](https://hub.docker.com/u/kubernets)

use shell script to pull docker image and replace origin tag

> wget https://github.com/kubernets/kube-proxy/raw/master/get-kube-proxy-image.sh

## Arch and Version

- [**amd64** v1.11.2](https://hub.docker.com/r/kubernets/kube-proxy-amd64)

    > docker pull kubernets/kube-proxy-amd64:v1.11.2

    > docker tag kubernets/kube-proxy-amd64:v1.11.2 gcr.io/google-containers/kube-proxy-amd64:v1.11.2 

    > docker rmi kubernets/kube-proxy-amd64:v1.11.2
