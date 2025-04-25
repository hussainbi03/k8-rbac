# RBAC

REGION_CODE=us-east-1
CLUSTER_NAME=roboshop
ACC_ID=416472087231

### Permissions

* OIDC provider
```
eksctl utils associate-iam-oidc-provider \
    --region $REGION_CODE \
    --cluster $CLUSTER_NAME \
    --approve
```