# Python Hello World CI/CD Pipeline [![Python Pipeline](https://github.com/babul101/develop-a-ci-cd-pipeline-for-a-Python-script/actions/workflows/pipeline.yml/badge.svg)](https://github.com/babul101/develop-a-ci-cd-pipeline-for-a-Python-script/actions/workflows/pipeline.yml)

## CI/CD Pipeline

The CI/CD pipeline consists of two stages:

1. **Test Stage**: This stage tests the Python script by running it with a Python command.

2. **Artifact Creation Stage**: This stage creates an artifact if the first stage completes successfully.

## Workflow Overview

A GitHub Actions workflow is triggered on a push event to the repository. The workflow consists of two jobs:

1. **Test Job**: This job checks out the repository and tests the Python script.

2. **Artifact Creation Job**: This job checks out the repository and creates an artifact if the Test Job completes successfully.

