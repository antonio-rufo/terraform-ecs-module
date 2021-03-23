# AWS ECS Cluster Terraform Module #

This Terraform module creates an AWS ECS cluster.

## Requirements

| Name      | Version |
| --------- | ------- |
| terraform | >= 0.12 |

## Providers

| Name | Version |
| ---- | ------- |
| aws  | n/a     |

## Inputs

| Name                                             | Description                                                                    | Type     | Default | Required |
| ------------------------------------------------ | ------------------------------------------------------------------------------ | -------- | ------- | :------: |
| name                                             | The name of the cluster (up to 255 letters, numbers, hyphens, and underscores).| `string` | n/a     |   yes    |


## Outputs

| Name                               | Description                                                                                            |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------ |
| aws\_ecs\_cluster\_cluster\_name   | The name of the cluster                                                                                |
| aws\_ecs\_cluster\_cluster\_id     | The Amazon ID that identifies the cluster                                                              |
| aws\_ecs\_cluster\_cluster\_arn    | The Amazon Resource Name (ARN) that identifies the cluster                                             |
