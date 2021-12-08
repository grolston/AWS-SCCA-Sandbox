# AWSomeBuilder 3

## AWS Multi Account Architecture

The following accounts were deployed to support the AB3 Landing Zone

| AWS Account | Functional Description |
| ----------- | ---------------------- |
| VDSS | Account manages the VDSS stack and networking for AB3 LZ |
| VDMS | Account contains all the shared managed services for AB3 LZ |
| Management | Account is the management account and orchestrates/delegates AWS Organization related services |
| MO1 Prod | Account is Mission Owner One Production account running customer-facing workloads |


## Networking

The following details the network CIDRs for the VPCs within the solution:

| AWS Account | Network | CIDR |
| ----------- | ------- | ---- |
| On-Premises | On-Premises VPC | 192.168.0.0/16 |
| VDSS | VDSS Stack | 10.0.0.0/16 |
| VDMS | VDMS Stack | 10.1.0.0/16 |
| MO1 Prod | Mission Owner 1 Production |  10.5.0.0/16 |
| MO1 Test | Mission Owner 1 Test |  10.6.0.0/16 |
| MO1 Dev | Mission Owner 1 Development |  10.7.0.0/16 |