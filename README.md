# AWS CLI

## Codebuild Command
```bash
aws codebuild create-project --cli-input-json file://<json>
aws codebuild update-project --cli-input-json file://<json>
aws codebuild delete-project --cli-input-json file://<json>

aws codebuild start-build --project-name  <project name>
aws codebuild delete-project --name <project name>
```