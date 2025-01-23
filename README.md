# Azure Red Hat OpenShift (ARO) Deployment using ARM Template

This repository contains an **Azure Resource Manager (ARM) template** to deploy an **Azure Red Hat OpenShift (ARO) cluster** with necessary networking and role assignments.

## 📌 Features
- Deploys an **ARO cluster** with configurable worker and master nodes.
- Sets up **Virtual Network (vNet)** and required **subnets**.
- Assigns necessary **permissions** for AAD integration.
- Allows configuring **API server and ingress visibility** (Public/Private).
- Provides **output credentials** for accessing OpenShift.

## 🚀 Deployment Instructions

### **1. Deploy using Azure CLI**
```sh
az deployment group create --resource-group <your-resource-group> --template-file azuredeploy.json
