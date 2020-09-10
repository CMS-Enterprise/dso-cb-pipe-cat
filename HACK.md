This repository hosts example pipelines for CloudBees CI:
- https://jenkins-east.cloud.cms.gov/
- https://jenkins.west.cloud.cms.gov/

A multi-branch pipeline can be found on the tooling master:
https://jenkins-east.cloud.cms.gov/tooling/job/cmscloud-infra-jenkins-examples/

Each example branch is built in that job.

Additional credentials may be needed if you are building pipelines with external services like SonarQube or JFrog. We use the Credentials Binding Plugin to manage these logins. Use service accounts where possible.
