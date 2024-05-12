## Build et lancement des conteneurs

```bash
docker-compose up
```

## Pour créer les images back et front sans compose

Commandes à exécuter à la racine du projet

- ```bash
  docker build -t leotepedelen/bff:latest ./bff/target
  ```
- ```bash
  docker build -t leotepedelen/front:latest ./front/browser
  ```
## Pour figer une image avec un tag

Exemple :

```bash
docker image tag leotepedelen/front:latest leotepedelen/front:1.0
```

## Publier une image sur Docker Hub

Exemples :

- ```bash
  docker push leotepedelen/front:latest
  ```

- ```bash
  docker push leotepedelen/front:1.0
  ```

- ```bash
  docker push leotepedelen/bff:latest
  ```

## Liste des images publiques

Exemples à retrouver sur Docker Hub, utilisateur `leotepedelen`

