---
name: Databricks Resource
about: Databricks Resource Issue Template
title: '[Databricks] <title>'
labels: Databricks
assignees: heeroyuy925
---

<!-- Please notice that this Template is only to be used when changes are done to Databricks resources.-->

## Description:
  * What does this Pull Request do?
  * What is the reasoning behind it?

## Databricks resources updated by this PR
Place an '[x]' (no spaces) in all applicable resources

  * [ ] Interactive Cluster
  * [ ] Group, User & Service Principal
  * [ ] Instance Pool
  * [ ] Cluster Policy
  * [ ] Secret Scope & Secret
  * [ ] Job
  * [ ] Personal Access Token

## Check Lists
Place an '[x]' (no spaces) in all check list you have done

  * [ ] Run `terraform fmt` before the PR raised
  * [ ] Keep `provider.tf` and `versions.tf` are follow the same content defined in `terragrunt.hcl`
  * [ ] Do not raise multiple change in different root folder. If so, please split PR into multiple PRs for different root folder.
  * [ ] Set the right reviewers

## Reference Documentation

You can refer the following documentations for provision resource.

  * [Databricks Onboarding Documentation for Provisioning Resources](https://farfetch.atlassian.net/wiki/spaces/DataStrategy/pages/3351183454/Onboarding+Guide+to+Databricks+Workspace)
  * [Databricks Personal Access Token](https://farfetch.atlassian.net/wiki/spaces/DataStrategy/pages/1626249646/Creating+Databricks+token+in+terraform)
  * [Getting Access to Databricks Workspace for Group & User](https://farfetch.atlassian.net/wiki/spaces/DataStrategy/pages/3223131425/Getting+Access+to+Databricks+Workspace)
  * [Create Service Principal](https://farfetch.atlassian.net/wiki/spaces/DataStrategy/pages/1620704192/Create+Service+Principal+Terraform)

## Reviewers:
  * @xjfan
  * @heeroyuy925
  * @dfeddad
  * @yriveiro
  * @sudeepgupta90
  * @nuno-silva18
