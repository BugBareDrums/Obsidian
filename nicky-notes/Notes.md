# Notes for [[Priority deployment]]

CSM Staging API - http://10.208.16.30


Account id - 546384338273

VPC link can only link to network load balancers

## AWS flow

```mermaid
graph LR; 
API_Gateway --> VPC_Link; 
VPC_Link --> NLB; 
NLB --> Target_Group; 
Target_Group --> ECS;
```

## AWS CLI
Azure tenant id:
9136de8a-8338-494e-97fb-347b2df1d48b

App id:
95f5939e-7f7c-4e30-a1f0-4e092f5979f4

