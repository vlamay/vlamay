# 👋 Hi, I'm Vladyslav

I'm a **DevOps Engineer** from Europe with a strong background in **System Administration, Cybersecurity**, and **IT Automation**.

I specialize in building **secure, automated CI/CD pipelines**, deploying scalable applications with **Docker, Kubernetes, and GitHub Actions**, and delivering **production-ready cloud solutions**.

I'm currently focused on improving my skills in **DevOps, Cloud Platforms**, and **Infrastructure as Code** — and I build portfolio projects to demonstrate it.

---

## 📦 Project Structure

```
.
├── cpp-service/
├── csharp-service/
├── java-service/
├── python-service/
├── docker-compose.yml
├── Makefile
├── .github/workflows/ci.yml
└── docs/
    └── architecture.png
```

---

## ⚙️ Features

- Multi-language microservices (C++, C#, Java, Python)
- GitHub Actions CI/CD with matrix builds and curl testing
- Docker Compose for local orchestration
- Kubernetes-ready with Helm support (coming soon)
- `/metrics` endpoints for Prometheus compatibility
- Modular folder structure with individual Dockerfiles
- Makefile with `make up`, `make test`, `make deploy`

---

## 🧠 Tech Stack

| Category       | Tools                            |
|----------------|----------------------------------|
| Containers     | Docker, docker-compose           |
| CI/CD          | GitHub Actions                   |
| Monitoring     | Prometheus, Grafana              |
| Languages      | C++, C#, Java, Python            |
| Kubernetes     | Minikube (optional)              |
| Security       | Trivy, Hadolint, docker scan     |

---

## ✅ Quick Start

### 🐳 Docker Compose

```bash
docker-compose up --build
```

### 🔁 GitHub Actions CI

Auto-triggers on push/pull request. Matrix build:

- Build Docker image
- Run container
- Curl test on `/health` and `/metrics`

---

## 📊 Monitoring (Optional)

To enable metrics scraping and dashboards:

1. Install Prometheus + Grafana in Minikube
2. Services expose `/metrics` endpoints
3. Screenshots available in `docs/metrics.md`

---

## 📄 Makefile

```bash
make up        # docker-compose up
make test      # curl tests
make deploy    # kubectl apply -f k8s/
```

---

## 🛡️ DevSecOps

- `.env.example` and `.gitignore` configured
- GitHub secrets: `GITHUB_TOKEN`, `FLY_API_TOKEN`
- CI includes: `trivy`, `hadolint`, `yamllint` (optional setup)

---

## 📚 Documentation

- [`docs/architecture.png`](docs/architecture.png)
- [`docs/metrics.md`](docs/metrics.md) – monitoring screenshots

---

## 🔗 Links

- [LinkedIn](https://www.linkedin.com/in/maidaniuk)
- [Resume (PDF)](https://github.com/vlamay/resume/blob/main/maidaniuk-devops-resume.pdf)

---

## 🏆 Achievements

- Full CI/CD across multi-language services
- Metrics-ready microservices
- Organized and documented DevOps project
