kops cluster with default settings (1 master node and 2 worker nodes) creates 21 AWS resources in the region in which the cluster is created (counted in Tag Editor).

kops uses [nodeup](https://github.com/kubernetes/kops/blob/master/pkg/model/resources/nodeup.go) instead of kubeadm.

Explanations about how kops works: https://kubernetes-kops.netlify.app/boot-sequence/

If creating Terraform output (`--target terraform`), the kubeconfig is created before the creation of any resources (after kops create cluster).
