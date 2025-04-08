# Frontend-ops

[Repositório de Código](https://github.com/Adenilson365/devopslabs01-api-images)

- Armazena os manifestos a serem aplicados no Kubernetes usando ArgoCD.

### Estrutura de pastas
```
.
├── application
│   ├── config
│   │   ├── frontend-config.yaml
│   │   └── frontend-hpa.yaml
│   ├── deployments
│   └── services
│       └── frontend-service.yaml
└── README.md

```

### Dependências
- Aplicação: [api-images](https://github.com/Adenilson365/devopslabs01-api-images)
- Aplicação: [catalogo](https://github.com/Adenilson365/devopslabs01-catalogo)

### Aplicar no cluster antes dessa aplicação:
- Não há