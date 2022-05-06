# gitops-model

POC model of how to use helm-dependencies to manage customisations to helm values.yaml files on a per environment/region/customer basis

```
.
├── customer1
│   ├── vault-config
│   │   ├── Chart.yaml      # --- > helm repo
│   │   └── values.yaml     # Overrides
│   └── vault-gitops.yaml   # ArgoCD manifest
└── customer2
    ├── vault-config
    │   ├── Chart.yaml
    │   └── values.yaml
    └── vault-gitops.yaml
```
