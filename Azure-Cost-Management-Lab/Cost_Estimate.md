# Azure Cost Estimation Report

## Overview
This report provides a cost estimation for deploying a simple 2-tier application using the Azure Pricing Calculator. The architecture includes frontend and backend virtual machines, storage, a SQL database, and outbound data transfer.

## Estimated Costs Breakdown

### 1. Frontend
- **Virtual Machine**: Standard B2s
- **Storage**: 50 GB
- **Region**: East US
- **Estimated Monthly Cost**: US$137.24

### 2. Backend
- **Virtual Machine**: Standard D2s_v3
- **Storage**: 100 GB
- **SQL Database**: Basic Tier
- **Region**: East US
- **Estimated Monthly Cost**: US$383.14 + US$290.84 = 673.98

### 3. Networking
- **Outbound Data Transfer**: 200 GB
- **Estimated Monthly Cost**: US$9.75

## Total Estimated Cost
**Total Monthly Cost**: $137.24+$383.14 + $290.84 +$9.75 = $820.97

## Additional Notes
- Prices may vary based on selected region and usage.
- The estimate does not include additional services like monitoring, backups, or security features.


---
**Generated using the Azure Pricing Calculator**

