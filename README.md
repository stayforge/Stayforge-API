# Stayforge API

[![Go Version](https://img.shields.io/badge/Go-1.25+-00ADD8?style=for-the-badge&logo=go)](https://golang.org)
[![API Version](https://img.shields.io/github/v/release/stayforge/Stayforge-API?sort=semver&display_name=tag&style=for-the-badge)](https://github.com/stayforge/Stayforge-API/releases/latest)
[![OpenAPI](https://img.shields.io/badge/OpenAPI-3.0.3-6BA539?style=for-the-badge&logo=openapiinitiative)](./openapi.yaml)
[![Gin Framework](https://img.shields.io/badge/Gin-Framework-00ADD8?style=for-the-badge)](https://github.com/gin-gonic/gin)

[![Better Stack Badge](https://uptime.betterstack.com/status-badges/v2/monitor/2a9d9.svg)](https://status.stayforge.io)
[![codecov](https://codecov.io/gh/stayforge/api.stayforge.net/graph/badge.svg?token=90eU6Z6W0E)](https://codecov.io/gh/stayforge/Stayforge-API)
[![Made with Love](https://img.shields.io/badge/Made%20with-❤-red?style=flat-square)](https://stayforge.net)


---

## 📖 Overview

The Stayforge API provides programmatic access to the Stayforge platform via a RESTful interface. This repository serves as the **official documentation hub and issue tracker**.

#### Quick Links
* **Documentation:** [Official Guides](https://docs.stayforge.io/apis/stayforge-api/overview) & [API Reference](https://docs.stayforge.io/apis/stayforge-api/v1/)
* **Specification:** [openapi.json](https://stayforge.github.io/Stayforge-API/openapi.json) / [openapi.yaml](https://stayforge.github.io/Stayforge-API/openapi.yaml)
* **Community:** Discord：https://discord.gg/JYFEttnydq

#### How to get a APIKey?

Manage your keys in here: https://dash.stayforge.io/settings/apikeys

Then, Put APIKey to Header `X-API-Key`:
```bash
curl -X GET "https://api.stayforge.net/v1/endpoint" \
     -H "X-API-Key: YOUR_API_KEY_HERE" \
     -H "Content-Type: application/json"
```

#### About OpenAPI & SDK

We are currently developing official SDKs for multiple languages, including Node.js, Python, Go, Java, and C#, all generated from and strictly aligned with this OpenAPI specification.

[openapi.json](https://stayforge.github.io/Stayforge-API/openapi.json) / [openapi.yaml](https://stayforge.github.io/Stayforge-API/openapi.yaml)

Before the official SDKs are released, you can already start integrating with our APIs by leveraging community-maintained OpenAPI tooling. In particular, for TypeScript projects, we recommend using `openapi-typescript` to generate type-safe client definitions directly from our OpenAPI schema, enabling rapid and reliable development.

> [!TIP]
> **Need help or found a bug?**
>
> For real-time support, join our [Discord](https://discord.gg/JYFEttnydq).
>
> To report bugs or documentation inconsistencies, please open a [GitHub Issue](https://github.com/stayforge/Stayforge-API/issues).

---

## 🛠 What You’ll Find Here

* 📄 **Documentation Metadata** – Links and schemas for the official Stayforge API.
* 🐛 **Issue Tracking** – A centralized place to report bugs or unclear API behavior.
* ✨ **Feedback** – Suggestions for improving examples or explanations.

---

## 🚀 Contributing & Issues

We welcome contributions to improve our documentation!

### Submitting Issues
Please use our [Issue Templates](https://github.com/stayforge/Stayforge-API/issues/new/choose) for:
* **Bug Report** — For errors or inconsistencies in the documentation.
* **Feature Request** — For suggestions or improvements.
* **Documentation Issue** — For unclear, missing, or misleading documentation.

### Workflow
1. **Fork** the repository.
2. **Make changes** (Markdown or schema updates).
3. **Open a Pull Request** with a clear description of the improvement.

---

## 🛡 License
*Stayforge API Documentation is maintained by the Stayforge Team.*
