# k8s-chestwood-course

## Usefull commands:
* kubectl describe svc "service-name"
* kubectl get po --show-labels
* kubectl delete pods "pod-name"
* kubectl delete rs "replica-set-name"
* kubectl rollout status deploy webapp
* kubectl rollout history deploy webapp
* kubectl rollout undo deploy webapp --to-revision=2
* kubectl delete -f .