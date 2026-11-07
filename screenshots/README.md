# Phase 3 screenshots

This folder belongs to the `ecommerce-kubernetes-manifests` repository's Phase 3 application-deployment documentation. Put the screenshots listed below in this folder. The Phase 3 section in the repository's root `README.md` embeds them with relative links.

| Filename | What it demonstrates |
|---|---|
| `01-argocd-apps-synced-healthy.png` | Argo CD applications reporting Synced and Healthy |
| `02-shop-homepage.png` | Deployed Astronomy Shop frontend |
| `04-ai-chatbot-working.png` | Deployed Astronomy Shop AI assistant |
| `05-grafana-spanmetrics-real-service-metrics.png` | Real service telemetry in Grafana |
| `06-jaeger-chatbot-traces.png` | Distributed chatbot traces in Jaeger |
| `12-opensearch-application-logs.png` | Application logs in OpenSearch Dashboards |

The ECR build-and-push workflow screenshot belongs in the `ecommerce-devsecops-platform` repository because it documents that repository's CI pipeline. Infrastructure and SonarQube screenshots belong with the Phase 1 and Phase 2 infrastructure documentation.

## Copy the screenshots from the desktop showcase folder

From Git Bash, while your current directory is the root of the cloned `ecommerce-kubernetes-manifests` repository, run:

```bash
mkdir -p screenshots
cp "/c/Users/bisol/OneDrive/Desktop/Astronomy-Shop-Project-Showcase/01-argocd-apps-synced-healthy.png" screenshots/
cp "/c/Users/bisol/OneDrive/Desktop/Astronomy-Shop-Project-Showcase/02-shop-homepage.png" screenshots/
cp "/c/Users/bisol/OneDrive/Desktop/Astronomy-Shop-Project-Showcase/04-ai-chatbot-working.png" screenshots/
cp "/c/Users/bisol/OneDrive/Desktop/Astronomy-Shop-Project-Showcase/05-grafana-spanmetrics-real-service-metrics.png" screenshots/
cp "/c/Users/bisol/OneDrive/Desktop/Astronomy-Shop-Project-Showcase/06-jaeger-chatbot-traces.png" screenshots/
cp "/c/Users/bisol/OneDrive/Desktop/Astronomy-Shop-Project-Showcase/12-opensearch-application-logs.png" screenshots/
```

Copy the Phase 3 section from `Phase-3-README-addition.md` to the end of the existing root `README.md`. Then review `git status`, stage the README and selected screenshots, commit, and push to `main`.
