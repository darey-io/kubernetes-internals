# Kubernetes Internals
A collection of resources that discuss the inner workings of [Kubernetes](https://kubernetes.io/).
Please not that this material _may not_ be relevant if you're looking to operate Kubernetes. This is aimed at folks curious about how Kubernetes works and does things internally.

## Blog Posts

### Networking
- [Kubernetes 101 - Networking](http://www.dasblinkenlichten.com/kubernetes-101-networking/)
- [Understanding kubernetes networking: pods](https://medium.com/google-cloud/understanding-kubernetes-networking-pods-7117dd28727)
- [Understanding kubernetes networking: services](https://medium.com/google-cloud/understanding-kubernetes-networking-services-f0cb48e4cc82)
- [Understanding kubernetes networking: ingress](https://medium.com/google-cloud/understanding-kubernetes-networking-ingress-1bc341c84078)

### Scheduler
- [How does the Kubernetes scheduler work](https://jvns.ca/blog/2017/07/27/how-does-the-kubernetes-scheduler-work/)
- [Scheduling in Kubernetes](http://alexandrutopliceanu.ro/post/scheduling-in-kubernetes/)
- [Implementing Advanced Scheduling Techniques with Kubernetes](https://thenewstack.io/implementing-advanced-scheduling-techniques-with-kubernetes/)

### API Server
- [Kubernetes deep dive: API Server – part 1](https://blog.openshift.com/kubernetes-deep-dive-api-server-part-1/)
- [Kubernetes deep dive: API Server – part 2](https://blog.openshift.com/kubernetes-deep-dive-api-server-part-2/)
- [Kubernetes deep dive: API Server – part 3a](https://blog.openshift.com/kubernetes-deep-dive-api-server-part-3a/)

## Talks

### Networking
- [The ins and outs of networking in Google Container Engine and Kubernetes](https://www.youtube.com/watch?v=y2bhV81MfKQ)
- [Deep-dive on Kubernetes networking](https://skillsmatter.com/skillscasts/10466-deep-dive-on-kubernetes-networking)
- [Life of a Packet](https://www.youtube.com/watch?v=0Omvgd7Hg1I)

## Docs/Design Proposals
Please be aware that the design proposals maybe not mirror the implementation exactly but convey the basic idea of the design.
### Networking
- [GKE Networking Overview](https://cloud.google.com/kubernetes-engine/docs/concepts/network-overview)
(Useful resource for understanding networking in general)
- [Design Proposals](https://github.com/kubernetes/community/tree/master/contributors/design-proposals/network)

### Scheduler
- [Sheduling algorithms](https://github.com/kubernetes/community/blob/master/contributors/devel/scheduler_algorithm.md)
- [Scheduler overview](https://github.com/kubernetes/community/blob/master/contributors/devel/scheduler.md)
- [Design Proposals](https://github.com/kubernetes/community/tree/master/contributors/design-proposals/scheduling)
