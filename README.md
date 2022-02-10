[![bicepBuild](https://github.com/PieterbasNagengast/AzurePolicy-DenySubnetSize/actions/workflows/bicepBuild.yml/badge.svg)](https://github.com/PieterbasNagengast/AzurePolicy-DenySubnetSize/actions/workflows/bicepBuild.yml)

# Azure Policy: Deny Subnet Size

## Description

Azure custom Policy Initiative definition including policy definitions:

- [Deny Subnet Size](https://github.com/PieterbasNagengast/AzurePolicy-DenySubnetSize)
- [Deny equal Address space and Subnet size](https://github.com/PieterbasNagengast/AzurePolicy-DenyEqualSubnetSizeAndAddressSpace)
- [Max Address space](https://github.com/PieterbasNagengast/AzurePolicy-VNETMaxAddressSpaces)

> **_NOTE:_** Template uses Linked Templates to above mentioned repos

## Background/Use case

tbd

> **_NOTE:_** tbd

## Deploy

Deploy Policy to Management Group or Subscription level.
Assign policy and provide paramters:
- Denied Subnet size (e.g. /24)
- Max allowed Address spaces (e.g. 1)
- Effect type of each policy (Deny, Audit, Disbaled)

| Description | Template |
|---|---|
| Deploy to Azure Management Group| [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FPieterbasNagengast%2FAzurePolicySet-VNETAddressGuardRails%2Fmain%2FVNET-Address-Guard-rails-MgmtGrp.json)|
| Deploy to Azure Subscription | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FPieterbasNagengast%2FAzurePolicySet-VNETAddressGuardRails%2Fmain%2FVNET-Address-Guard-rails-Sub.json)|
