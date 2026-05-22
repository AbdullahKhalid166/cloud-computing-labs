# Lab 07 – CI/CD using AWS CodePipeline

## Objective
To implement a CI/CD pipeline using AWS services for automated build and deployment.

---

## Tasks Performed
- Created an S3 bucket to store deployment files
- Created CodeCommit repository for source code
- Uploaded application code to repository
- Created build configuration file
- Set up CodeBuild project for building code
- Created CodePipeline with Source, Build, and Deploy stages
- Observed pipeline execution on code changes
- Modified code to test pipeline behavior
- Introduced an error to analyze failure logs

---

## Key Implementation
- Source stage pulls code from CodeCommit
- Build stage processes using CodeBuild
- Deploy stage stores output in S3
- Pipeline triggers automatically on changes
- Error logs analyzed when configuration was incorrect

---

## Result
Successfully implemented an automated CI/CD pipeline and analyzed its behavior during normal and error conditions.

---

## Learning Outcomes
- Understanding CI/CD concepts
- Integration of AWS developer tools
- Pipeline automation workflow
- Debugging build and deployment failures
``
