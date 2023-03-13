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
  Command Tools base on AWS Command For Codebuild

AVAILABLE 'ARG':

  --build-one          Build Project
  --list-all           List Project
  --export-all         Export All Codebuild Project
  --create-webhook     Create auto build trigger webhook on project
  --delete-webhook     Delete webhook on project
  --create-new         Create New Project include webhook
  --update-one         Update project
  --delete-one         Delete project

USAGE:
./awscli <ARG> <PROJECT NAME>

```