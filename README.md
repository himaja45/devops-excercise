Installed minikube in VirtualBox.
created namespace using kubectl create ns namespace-name command.
created pod with nginx image using imperative command.
Exposed the nginx pod as a service to nodeport.
Edited the nodeport to 32700.
To visit the nginx pod from local machine on port 32700 used minikube service service-name -n namespace name --url.
Using kubectl get pod pod-name -n namespace-name -o yaml > pod-name.yaml command downloaded the yaml files.
