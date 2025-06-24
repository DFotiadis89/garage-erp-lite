# garage-erp-lite

**Modular ERP for automotive repair shops**, built from scratch as a learning and portfolio project.  
Initially developed for self-hosting on a Raspberry Pi cluster, with the goal of cloud migration and production-readiness.

---

## 🚗 Project Goals

- Build a modular, containerized ERP tailored for **automotive service garages**
- Start with **Raspberry Pi deployment**, migrate to **cloud infrastructure** (e.g. Azure)
- Showcase practical experience with:
  - .NET Web API development
  - Docker + Kubernetes orchestration
  - CI/CD pipelines using GitHub Actions
  - Infrastructure observability (logging, metrics, dashboards)
- Prioritize clean code, modular architecture, and production-relevant practices
- Publish project publicly with documentation and deployment walkthroughs

---

## ⚙️ Tech Stack (Planned)

| Layer             | Technology                  | Purpose                                                      |
|------------------|-----------------------------|--------------------------------------------------------------|
| **OS**           | Ubuntu Server (Pi & Cloud)  | Stable, lightweight OS                                       |
| **Orchestration**| k3s (lightweight Kubernetes)| Lightweight cluster for self-hosting and scaling             |
| **Containers**   | Docker                      | Standard container runtime                                   |
| **Backend**      | .NET 8 Web API              | Business logic, service endpoints                            |
| **Frontend**     | HTML/CSS/JS                 | Admin-facing interface                                       |
| **Database**     | PostgreSQL                  | Relational database for business data                        |
| **Ingress**      | Traefik *(or Nginx)*        | HTTPS, routing, service discovery                            |
| **Monitoring**   | Grafana + Loki + Prometheus | Full-stack observability                                     |
| **CI/CD**        | GitHub Actions              | Automated build, test, and deployment pipelines              |

---

## 🔨 MVP Modules

1. **Clients & Vehicles**  
   Store client contact info and track multiple vehicles per customer

2. **Work Orders**  
   Manage ongoing/past jobs, assigned technician, services, and parts used

3. **Invoices**  
   Tied to work orders; printable/exportable; tracks payment status

---

## 📦 Status

- [ ] Project scaffolding
- [ ] Initial backend service setup
- [ ] Local Docker Compose dev environment
- [ ] First MVP module (Clients & Vehicles)
- [ ] Raspberry Pi deployment
- [ ] Cloud migration setup (AKS or similar)

---

## 📘 License

_To be added — likely MIT_

