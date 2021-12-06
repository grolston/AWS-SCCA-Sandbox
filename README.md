# AWSomeBuilder 3

## AWS Multi Account Architecture

The following accounts were deployed to support the AB3 Landing Zone

| AWS Account | Functional Description |
| ----------- | ---------------------- |
| VDSS | Account manages the VDSS stack and networking for AB3 LZ |
| VMDS | Account contains all the shared managed services for AB3 LZ |
| Management | Account is the management account and orchestrates/delegates AWS Organization related services |
| MO1 Prod | Account is Mission Owner One Production account running customer-facing workloads |


## Networking

The following details the network CIDRs for the VPCs within the solution:

| AWS Account | Network | CIDR |
| ----------- | ------- | ---- |
| On-Premises | On-Premises VPC | 192.168.0.0/16 |