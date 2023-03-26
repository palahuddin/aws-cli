# AWS CLI

## Codebuild Command
```bash
aws codebuild create-project --cli-input-json file://<json>
aws codebuild update-project --cli-input-json file://<json>
aws codebuild delete-project --cli-input-json file://<json>

aws codebuild start-build --project-name  <project name>
aws codebuild delete-project --name <project name>
```

## PREREQUISITE
- [jq](https://stedolan.github.io/jq/)
- [aws cli](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)

## USAGE
```bash
  Command Tools base on AWS Command

AVAILABLE 'ARG':

  --build-one          Build codebuild project
  --list-all           List codebuild project
  --export-all         Backup codebuild project as json file
  --create-webhook     Create webhook codebuild project
  --update-webhook     Update webhook codebuild project
  --delete-webhook     Delete webhook codebuild project   
  --create-new         Create new codebuild project including webhook 
  --update-one         Update codebuild project   
  --delete-one         Delete codebuild project   
  --scale-ng           Scale Up nodegroup eks 
  --ng                 Get EKS Cluster nodegroup list
  --init-pv            Setup EKS Cluster persistence volume AWS EBS Driver  

USAGE:
./awscli <ARG> <PROJECT NAME>

```