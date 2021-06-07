# Terraform
## Introduction
When building in a cloud environment, resources can usually be created by manipulating a large number of screens and input forms on the cloud.  
However, since manual work is required every time, there are problems such as increased work time and setting mistakes.  
In recent years, in order to solve this problem, a method called IaC (Infrastructure as Code), which manages and provisions infrastructure using code, has been attracting attention and being utilized.  
This page provides a sample script of Terraform, an automatic infrastructure construction tool.  

## What is Terraform?
An open source infrastructure automatic construction tool developed by HashiCorp.  
It is mainly used when building a cloud environment (which can be used outside the cloud).  
You need to create and maintain Terraform configuration files. However, it is possible to construct various environments in a programmable manner faster and without mistakes than by manual work, and work costs and work mistakes can be reduced.  

## Directory structure
```
Terraform
    |- OCI
    |   |- clp-lin-2node-lb-md.zip (2node mirror disk cluster (Linux))
    |   |- clp-win-2node-lb-md.zip (2node mirror disk cluster (Windows))
    |
    |- README_JP.md
    |- README.md
```

## Reference
[I tried to automatically build an HA cluster environment using Resource Manager on Oracle Cloud Infrastructure (Windows / Linux)
EXPRESSCLUSTER Official Blog-Clublo-](https://translate.google.com/translate?sl=ja&tl=en&u=https://jpn.nec.com/clusterpro/blog/20210531.html?)  

(We translated using the automatic translation function by Google Translate.)
