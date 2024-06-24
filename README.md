AWS Backup for S3 Using Tags
---
## Overview

CDK example to create a AWS Backup Vault and backup an S3 bucket which has Resource Tags assigned to it.
Once deployed, any uploaded object in the bucket created will be backed up once the backup schedule is executed.

## Prerequisites

```
$ npm install -g typescript
$ npm install -g aws-cdk
$ aws configure
```
## Build and Deploy

The `cdk.json` file tells the CDK Toolkit how to execute your app.
Before getting ready to deploy, ensure the dependencies are installed by executing the following:
```
$ npm install
```
### CDK Bootstrap

```
cdk bootstrap
```

### CDK Deploy

Using the default profile

```
$ cdk deploy
```
