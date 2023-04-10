# rke2-template

RKE2 Cluster Templates to provision a Kubernetes clusters on AWS
The template consists of 1 ControlPlane/etcd node and one worker node.  

The control plane/etcd node is sized to t3a.medium and worker node is t3a.large

## How to Use

* Go to the Apps Marketplace in the `local` cluster in Rancher
* Add a new Chart Repository to the HTTP(S) URL `https://firefhtr.github.io/rancher-cluster-templates` without authentication
