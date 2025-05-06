# Azure Landing Zones Terraform Module

> ⚠️ **Important**  
> For new deployments, we recommend using the [Azure Verified Modules for Platform Landing Zones](https://aka.ms/alz/tf).  
> This module will continue to be supported for **existing deployments**.

---

## 🔧 Build Status

| Release | Issue Resolution Time | Open Issues % | OpenSSF Scorecard |
|---------|------------------------|---------------|--------------------|
| ![GitHub release](https://img.shields.io/github/v/release/sre-world/terraform-landing-zone-core) | ⏱️ Avg: X days | ✅ Y% Closed | 🔒 Z/10 |

---

## 📘 Documentation

> Please refer to the [Wiki](https://github.com/sre-world/terraform-landing-zone-core/wiki) for complete usage, configuration, and customization guidance.

- [🏠 Home](https://github.com/sre-world/terraform-landing-zone-core/wiki)
- [📖 User Guide](https://github.com/sre-world/terraform-landing-zone-core/wiki/User-Guide)
- [💡 Examples](https://github.com/sre-world/terraform-landing-zone-core/wiki/Examples)
- [❓ FAQ](https://github.com/sre-world/terraform-landing-zone-core/wiki/Frequently-Asked-Questions)
- [🛠️ Troubleshooting](https://github.com/sre-world/terraform-landing-zone-core/wiki/Troubleshooting)

---

## ⚠️ Upcoming Breaking Changes (Q4 2024)

The following **module defaults will change** to deploy **zone redundant SKUs** by default:

- Azure Firewall
- Public IP
- Virtual Network Gateway

> 📢 Detailed migration guidance will be published to avoid redeploying existing resources.

---

## 📌 Overview

This module is part of the enterprise Azure platform rollout and implements core components of the [Azure Landing Zones](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/landing-zones/) using [Terraform](https://www.terraform.io/).

It supports standardized deployment of:

- Management Groups & Hierarchies
- Azure Policies & Blueprints
- Diagnostic Settings
- Platform Logging & Monitoring
- Core Networking Architecture (Hub/Spoke ready)

---

## 🧭 Architecture

> A conceptual architecture diagram highlighting the design areas covered by the Azure landing zones Terraform module:

![ALZ Architecture](https://aka.ms/alz/architecture-diagram)

---

## 📂 Repo Structure (Sample)

