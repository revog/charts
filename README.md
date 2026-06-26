<div align="center">
  
# Helm Charts
_... self-made and public available for everyone to use._

</div>

---

## 📖 Overview
This repository serves self-made helm charts. Here I manage and maintain the charts. For documentation on specific charts look at README files within the chart directories.
This GitHub repo represents a self-hosted Helm charts repo using GitHub Container Registry - ghcr.io (OCI-based).

## ⚙ Installation
To use these charts, first add this repository to Helm:
```sh
helm repo add revog https://revog.github.io/helm-charts
helm repo update
```

Then, install a chart using:
```sh
helm install <release-name> revog/<chart-name>
```

## 👥 Contributing
The project welcomes contributions from any member of the OSS community. To get started contributing, please see our [Contributor Guide](.github/CONTRIBUTING.md).
