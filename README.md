# tasks-config : dépôt de configuration (jour 4, GitOps)

Dépôt de configuration surveillé par **Argo CD** pour déployer [tasks-api](https://github.com/Delprogram/tasks-api).

```
k8s/
  deployment.yaml   les pods de l'application et l'image à utiliser
  service.yaml      l'exposition de l'application dans le cluster
```

Règle d'or du GitOps : on ne modifie jamais le cluster à la main, on modifie ce dépôt.
