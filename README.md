# gitops-model

POC model of how to use helm-dependencies to manage customisations to helm values.yaml files on a per environment/regin/customer basis

.
├── customer1
│   ├── vault-config
│   │   ├── Chart.yaml
│   │   └── values.yaml
│   └── vault-gitops.yaml
└── customer2
    ├── vault-config
    │   ├── Chart.yaml
    │   └── values.yaml
    └── vault-gitops.yaml

