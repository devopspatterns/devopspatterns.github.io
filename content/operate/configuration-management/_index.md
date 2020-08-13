---
title: "Configuration Management"
date: 2020-08-10T14:46:38-04:00
---

1. Application configuration should exist seperately from application packaging
1. Applications should be independent of external configuration for their environment so that the same application package can run in multiple environments (DEV, QA, PROD)
1. Use secret management software (Azure KeyVault, Hashicorp Vault, Kubernetes Secrets, etc)
