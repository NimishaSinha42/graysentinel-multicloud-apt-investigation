# GraySentinel – Multi-Cloud APT Investigation

## Overview

This project documents a cloud-native Advanced Persistent Threat (APT) investigation across multiple cloud environments:

- AWS
- Microsoft Azure
- Google Cloud Platform (GCP)
- Kubernetes
- Elastic Stack

The objective of the lab was to perform cloud asset discovery, identify security misconfigurations, centralize cloud logs, audit Kubernetes security, and automate investigation evidence collection.

> This repository represents a controlled cybersecurity lab / training environment.  
> Credentials, IDs, domains, subscriptions, and cloud resources shown in the evidence may be simulated or sanitized.

---

## Objectives

The investigation focused on:

- Installing and validating cloud command-line tools
- Enumerating AWS resources
- Reviewing AWS EC2 security groups
- Enumerating Azure subscriptions and identities
- Discovering Azure service principals
- Enumerating GCP projects, VMs, and storage buckets
- Deploying an Elastic Stack environment
- Forwarding multi-cloud logs into Elasticsearch
- Running Kubernetes CIS benchmark checks
- Scanning Kubernetes for security weaknesses
- Automating multi-cloud evidence collection
- Creating a consolidated investigation report

---

# 1. Environment Preparation

The lab began by updating the Kali Linux package repository.

```bash
sudo apt update
