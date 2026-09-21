# 🚀 Next.js Docker + Helm + Minikube

A complete DevOps project demonstrating how to containerize a **Next.js application with Docker** and deploy it to **Kubernetes using Helm on Minikube**.

The project covers:

- Next.js application
- Docker multi-stage build
- Docker Hub
- Kubernetes
- Minikube
- Helm
- Helm Charts
- Helm repositories
- Kubernetes Deployment
- Kubernetes Service
- Environment variables
- Helm upgrade
- Helm rollback
- Kubernetes troubleshooting

---

## 📌 Architecture

```text
                         GitHub
                           |
                           v
                    Next.js Application
                           |
                           v
                      Dockerfile
                           |
                           v
                    Docker Build
                           |
                           v
                     Docker Image
                           |
                           v
                      Docker Hub
                           |
                           v
                      Helm Chart
                           |
             +-------------+-------------+
             |                           |
             v                           v
         Chart.yaml                  values.yaml
             |                           |
             +-------------+-------------+
                           |
                           v
                     Helm Templates
                           |
                           v
                    Kubernetes Manifests
                           |
                           v
                       Minikube
                           |
                           v
                  Kubernetes Deployment
                           |
                           v
                         Pod
                           |
                           v
                  Kubernetes Service
                           |
                           v
                        Browser