# Deploy to Azure as a Service

_This SaaS starter automates app deployments to Azure using GitHub Actions._

---

## Overview

This repository is designed to help teams deploy their applications to Azure with minimal configuration using GitHub Actions. It provides a production-ready automation workflow that allows developers to ship faster with confidence.

---

## What You Get with This SaaS Starter

- 🔖 **Label-triggered deployments**: Use labels like `deploy-staging`, `deploy-prod`, and `teardown` to control GitHub Actions workflows.
- ⚙️ **Azure environment automation**: Seamlessly set up and manage your Azure resources.
- 🚀 **One-click deployment**: Simple PR-based deployments to staging and production environments.
- 🧹 **Environment cleanup**: Automatically destroy temporary environments to save costs.
- 📦 **Template repository ready**: Use this as a boilerplate for new projects or customer deployments.

---

## How It Works

1. **Add a label** to your pull request, such as `deploy-staging`.
2. GitHub Actions detects the label and triggers the associated deployment workflow.
3. The app is deployed to the corresponding Azure environment.
4. Use the `teardown` label to destroy temporary resources when no longer needed.

---

## Usage

1. Clone this repository or use it as a **template**.
2. Set up Azure authentication using a service principal (already practiced).
3. Customize the workflows under `.github/workflows/` to match your application.
4. Push your code and use PR labels to control deployment.

---

## License

MIT License – see [LICENSE](LICENSE) file for details.

---

## Contact & Support

For questions or business inquiries, contact us:

- 📧 **Email:** [info@hoiltd.com](mailto:info@hoiltd.com)
- 🌐 **Enterprise:** [HOILTD GitHub Enterprise](https://github.com/enterprises/hoiltd)
- 🏢 **Organization:** [HOME-OFFICE-IMPROVEMENTS-LTD](https://github.com/HOME-OFFICE-IMPROVEMENTS-LTD)

&copy; 2025 Home & Office Improvements Ltd

