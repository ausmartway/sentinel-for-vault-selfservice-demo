# sentinel-for-cba-vault-demo

This repository contains some basic Sentinel policies to govern Vault configuration via Terraform Enterprise/Terraform Cloud.

This policy set is supposed to work with a Terraform Enterprise workspace that act as a super user for Vault. It allows users to provision a github repository, a vault namespace with associated admin token and policies and a Terraform Enterprise workspace that connects the two. sub-namespace users can then config their namespace by committing Terraform code to the github repository.
