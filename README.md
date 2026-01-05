# e2e-ML-deployment
ML Github Actions (CI) and AWS Beanstalk (CD) deployment practice

## Project Description

## Pipeline

Preparing for AWS Beanstalk
```bash
uv venv .venv-app
source .venv-app/bin/activate
uv pip install -r App/requirements.txt
uv add --active awsebcli
eb init -p python-3.11 drug-classification
```

## Results

## Resources
- https://github.com/kingabzpro/CICD-for-Machine-Learning
- https://www.youtube.com/watch?v=gbJn2Ls2QsI 
- https://docs.github.com/en/actions/reference/workflows-and-actions/workflow-syntax 