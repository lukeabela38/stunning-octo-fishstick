# stunning-octo-fishstick

## [K3Ds](https://k3d.io/stable)

## [Argocd](https://argo-cd.readthedocs.io/en/stable/)


```
infrastructure/
├── argocd/
│   ├── install/
│   │   └── kustomization.yaml   # Declares the ArgoCD base engine installation
│   └── root-application.yaml    # The single Bootstrap App that tracks this folder
└── apps/
    └── [your-helm-charts-here]  # Discovered automatically by your ApplicationSet
```
