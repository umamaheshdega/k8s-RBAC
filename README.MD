# RBAC
REGION_CODE=us-east-1 CLUSTER_NAME=expense ACC_ID=
---
## permission
  .OIDC driver

eksctl utils associate-iam-oidc-provider \
    --region $REGION_CODE \
    --cluster $CLUSTER_NAME \
    --approve