# Create Deployment with AWS ELB

```
kubectl get deployments
kubectl set image deploymen/helloworld-deployment basicnodeapp=buildmystartup/nodedbapp --record
kubectl set image deployment/helloworld-deployment basicnodeapp=buildmystartup/nodedbapp --record
kubectl deployment status
kubectl deployment status
kubectl rollout status deployment helloworld-deployment
curl http://40.113.193.117
kubectl rollout history deployment helloworld-deployment
kubectl rollout undo deployment/helloworld-deployment --to-revision=1
kubectl rollout status deployment helloworld-deployment
curl http://40.113.193.117
kubectl get pods
curl http://40.113.193.117
kubectl set image deployment/helloworld-deployment basicnodeapp=buildmystartup/basicnodeapp --record
kubectl get pods
curl http://40.113.193.117
kubectl rollout history deployment helloworld-deployment
kubectl rollout undo deployment/helloworld-deployment --to-revision=2
kubectl get pods
kubectl set image deployment/helloworld-deployment basicnodeapp=buildmystartup/nodedbapp --record
kubectl get pods
curl http://40.113.193.117
kubectl scale deployment/helloworld-live-readiness --replicas=3
 ```
