# Create Deployment with AWS ELB

```
kubectl get deployments
 5471  kubectl set image deploymen/helloworld-deployment basicnodeapp=buildmystartup/nodedbapp --record
 5472  kubectl set image deployment/helloworld-deployment basicnodeapp=buildmystartup/nodedbapp --record
 5473  kubectl deployment status
 5474  kubectl deployment status
 5475  kubectl rollout status deployment helloworld-deployment
 5476  curl http://40.113.193.117
 5477  kubectl rollout history deployment helloworld-deployment
 5478  kubectl rollout undo deployment/helloworld-deployment --to-revision=1
 5479  kubectl rollout status deployment helloworld-deployment
 5480  curl http://40.113.193.117
 5481  kubectl get pods
 5482  curl http://40.113.193.117
 5483  kubectl set image deployment/helloworld-deployment basicnodeapp=buildmystartup/basicnodeapp --record
 5484  kubectl get pods
 5485  curl http://40.113.193.117
 5486  kubectl rollout history deployment helloworld-deployment
 5487  kubectl rollout undo deployment/helloworld-deployment --to-revision=2
 5488  kubectl get pods
 5489  kubectl set image deployment/helloworld-deployment basicnodeapp=buildmystartup/nodedbapp --record
 5490  kubectl get pods
 5491  curl http://40.113.193.117
 ```
