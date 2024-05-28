## Jobs App - Terafform provisioning

`terraform, EKS, terraform-aws-modules`

Provision Kubernetes cluster for the [Jobs App](https://github.com/jkubacki/jobs-app)

[demo.jakubkubacki.com](https://demo.jakubkubacki.com)

![output](https://github.com/jkubacki/jobs-app/assets/1104186/1cf0a889-5ebf-4fcf-b5db-7652a4e3e972)

#### Features:
* Create high available managed EKS cluster with 3 nodes
* Add aws-ebs-csi-driver - volumes provisioning
* Security group config for ingress-nginx and sealed secrets
