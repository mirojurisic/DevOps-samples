# DevOps-samples
Singe app pipeline - goal automatic docker image build and push to ECR

Prerequisites:
0) Github repo with buildspec.yml step (pipeline instructions)
   ECR Repository created (repo name, region, account number)

1) create CodePipeline build project
    1.1) select github repo
    1.2) add policy to role to push to ECR
    1.3) set environmental variables (Optional)
    1.4) set webhook - private repo for more options and configure on pull request merge to run pipeline
