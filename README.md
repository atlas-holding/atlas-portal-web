# atlas-portal-web

atlas-portal-web service

## Stack
- Langage : ${{ values.language }}
- CI/CD : Tekton → Harbor → ArgoCD
- Plateforme : DxP

## Démarrage rapide
```bash
# Cloner le repo
git clone <repo-url>
cd atlas-portal-web

# Lancer en local
docker build -t atlas-portal-web .
docker run -p 8080:8080 atlas-portal-web
```
