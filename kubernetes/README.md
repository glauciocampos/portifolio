### [<img src="https://k3s.io/img/k3s-logo-light.svg" width="130" height="130" />](https://k3s.io/)

#### Why k3s?
It's lightweight, multiarch, supports high availability and works great on small production environments.

#### How it works:
<img src="https://www.suse.com/c/wp-content/uploads/2021/09/rancher_blog_k3s-architecture.jpeg" width="600" height="300" />

* A server node is defined as a host running the k3s server command, with control-plane and datastore components managed by K3s.
* An agent node is defined as a host running the k3s agent command, without any datastore or control-plane components.
* Both servers and agents run the kubelet, container runtime, and CNI. See the Advanced Options documentation for more information on running agentless servers.

#### Single-server Setup with an Embedded DB


<img src="https://docs.k3s.io/img/k3s-architecture-single-server-dark.svg" width="600" height="300" />