name: Databricks PR Template
description: This is the PR Template for request Databricks resources
title: "[Databricks] <title>"
labels: [Databricks]
body:
- type: textarea
  attributes:
    label: What does this Pull Request do?
    description: Please put the action here for this PR
    validations:
    - required: true
- type: textarea
  attributes:
    label: What is the reasoning behind it?
    description: Please put the purpose here why you raise this PR
    validations:
    - required: true
- type: textarea
  attributes:
    label: What is the reasoning behind it?
    description: Please put the purpose here why you raise this PR
    validations:
    - required: true
- type: checkbox
  attributes:
    label: Databricks resources provisiond by this PR
    description: You may select more than one applicable resources in this PR.
    options:
      - label: Interactive Cluster
      - label: Group, User & Service Principal
      - label: Instance Pool
      - label: Cluster Policy
      - label: Secret Scope & Secret
      - label: Job
      - label: Personal Access Token
- type: textarea
  attributes:
    label: Reference Documentation
    description: You can refer the following documentations for provision resource.
    placeholder: |
        * [Databricks Onboarding Documentation for Provisioning Resources](https://farfetch.atlassian.net/wiki/spaces/DataStrategy/pages/3351183454/Onboarding+Guide+to+Databricks+Workspace)
        * [Databricks Personal Access Token](https://farfetch.atlassian.net/wiki/spaces/DataStrategy/pages/1626249646/Creating+Databricks+token+in+terraform)
        * [Getting Access to Databricks Workspace for Group & User](https://farfetch.atlassian.net/wiki/spaces/DataStrategy/pages/3223131425/Getting+Access+to+Databricks+Workspace)
        * [Create Service Principal](https://farfetch.atlassian.net/wiki/spaces/DataStrategy/pages/1620704192/Create+Service+Principal+Terraform)
