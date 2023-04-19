## Notes ✨  
Once you're done, click on the save button to directly save your Readme to your
project's root directory!


Update the docker image name in a kubernetes config file
```
kubectl set image deployment/multi-deployment client=mcjovial/multi-client:v2
```

To swich to minikube's node's docker installation
```
eval $(minikube docker-env)
```

Trigger shell in a docker container
```
docker exec -it container_id sh