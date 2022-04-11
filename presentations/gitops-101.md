<!--
theme: default
class:
 - invert
headingDivider: 2 
paginate: true
-->

<!--
_class:
 - lead
 - invert
-->


# GitOps 101

Created in April 2022

## Definition - What?

> GitOps is an operational framework that takes DevOps best practices used for application development such as version control, collaboration,
compliance, and CI/CD, and applies them to infrastructure automation [GitLab](https://about.gitlab.com/topics/gitops/)

## Definition - Why?

* Break the strong coupling between component source code and infrasrtucture lifecycle
* Leverage all versioning features to infrastructure management

## Definition - How?

[![GitOps CD pipeline by WeaveWorks](./img/weaveworks-gitops_cd_pipeline.jpg)](https://www.weave.works/blog/gitops-high-velocity-cicd-for-kubernetes)

## Buzzword fight

Word | Main impact | Meaning
---- | ----------- | -------
CI/CD | Technical | Continuous automation pipelines
DevOps | People | Collaboration practices on a common goal
GitOps | Processes | Operational framework

## ArgoCD - Discovery

CNCF (Cloud Native Computing Foundation) tending project

## Demonstration

## Tips to start

* Start small, no big bang, with baby steps to evaluate, gather experience, and update the approach when needed
* Run the processes into containers and manage the workload with an orchestrator tool like Kubernetes
* Use state of the art tools like helm and ArgoCD

## Choices to make

* Environment strategy?
  * one per folder
  * one per git branche
  * one per git repository

## Interesting readings

* [Promoting changes and releases with GitOps](https://en.sokube.ch/post/promoting-changes-and-releases-with-gitops)
by SoKube - January 18, 2022
