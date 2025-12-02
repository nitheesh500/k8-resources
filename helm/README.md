# myapp – Nginx Helm Chart 

This is a beginner-friendly Helm chart that includes:

- Deployment
- Service
- Horizontal Pod Autoscaler (HPA)
- Environment-specific values (dev + prod)
- Clean & simple YAML (no advanced templating)

---

## 📁 Folder Structure

myapp/
│
├── Chart.yaml
├── values.yaml
├── values-dev.yaml
├── values-prod.yaml
├── README.md
│
└── templates/
    ├── deployment.yaml
    ├── service.yaml
    └── hpa.yaml
