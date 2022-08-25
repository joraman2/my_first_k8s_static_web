### README

This is an example of a simple NodePort service.

If you use minikube, in order to see something from the browser you need:

* to have some index.html saved in /data of the container that runs minikube
     
        docker ps | grep minikube
        docker exec -it <container id> bash 

and edit the index.html file with vi


* to know the minikube IP

        minikube ip 

Afterwards, you can see your web in http://< output from previous command >:30001/


