## Jobs App - Terafform provisioning

`terraform, EKS, terraform-aws-modules`

Provision Kubernetes cluster for the [Jobs App](https://github.com/jkubacki/jobs-app)

[demo.jakubkubacki.com](https://demo.jakubkubacki.com)

![output](https://github.com/jkubacki/jobs/assets/1104186/67827e74-db84-472d-aef1-efa86d02052d)

#### Features:
* Create high available managed EKS cluster with 3 nodes
* Add aws-ebs-csi-driver - volumes provisioning
* Security group config for ingress-nginx and sealed secrets
