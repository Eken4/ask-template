On ajoute 

  "engine":{
    "node":16
  } 
  
dans les fichiers package.json du repo

dans back/ et front/
yarn install pour installer les dépendances nécessaires
yarn install --dev prettier eslint

-> check fichiers de configuration, .prettierrc, .prettierignore

Dockerfiles différents pour back et front -> en fait non pas pour front
docker build .
Ensuite docker run basé sur l'image créée

Docker compose -> lancer l'image + la bdd Maria db avec les bonnes adresses
docker compose exec <nom docker>

Docker compose à la racine du projet
base de données back
serveur web front

docker-compose up
