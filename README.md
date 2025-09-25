# CISY 5183 - Lab 1: Azure Storage and ARM Template Export

This repository contains the exported ARM template from the Azure resource group `rg-lab01-<your-initials>` created during Lab 1 of CISY 5183.  

## Included
- Storage account baseline configuration
- Lifecycle management policy (tier-to-cool rule) when supported

## Not Included
- Actual blob data
- Some container-level settings (e.g., immutability policy) may not be captured by the export

## Purpose
The ARM template serves as a baseline for infrastructure-as-code, allowing replication or auditing of the lab resources.  
