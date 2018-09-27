[![Build Status](https://jenkins-terraform.mesosphere.com/service/dcos-terraform-jenkins/job/dcos-terraform/job/terraform-gcp-compute-firewall/job/master/badge/icon)](https://jenkins-terraform.mesosphere.com/service/dcos-terraform-jenkins/job/dcos-terraform/job/terraform-gcp-compute-firewall/job/master/)
# DC/OS Network Firewall Rules


## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| admin_ips | List of CIDR admin IPs | list | - | yes |
| internal_subnets | List of internal subnets to allow traffic between them | list | - | yes |
| name_prefix | Cluster Name | string | - | yes |
| network | network | string | - | yes |

## Outputs

| Name | Description |
|------|-------------|
| name_prefix | Cluster Name |
| network | Network Name |

