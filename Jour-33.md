# Objectifs journaliers

## Mercredi 30/10/2024 :

### Introduction à PostgreSQL et DCL

- [ ] Découverte de PostgreSQL
  - [ ] Identifier les différences entre MySQL et PostgreSQL
  - [ ] Savoir Expliquer les avantages de PostgreSQL
  - [ ] Savoir Choisir les cas d'usage adaptés à PostgreSQL

- [x] Installation et Configuration
  - [x] Installation de PostgreSQL sur la machine
  - [x] Installation de pgAdmin 4
  - [x] Installation de pgcli
  - [x] Configuration initiale
    - [x] Ports
    - [x] Mot de passe postgres
    - [x] Création du premier utilisateur
  - [x] Test de la connexion

- [x] Data Control Language (DCL)
  - [x] Gestion des utilisateurs
    - [x] Savoir construire des requêtes CREATE USER
    - [x] Savoir modifier des utilisateurs avec ALTER USER
    - [x] Savoir supprimer des utilisateurs avec DROP USER
    - [x] Savoir utiliser les rôles PostgreSQL
  
  - [ ] Gestion des droits
    - [ ] Savoir attribuer des privilèges avec GRANT
      - [ ] Droits sur les bases de données
      - [ ] Droits sur les tables
      - [ ] Droits sur les colonnes
    - [ ] Gérer la révocation avec REVOKE
      - [ ] Comment retirer des droits sur une base de données, une table ou une colonne ?
      - [ ] Quel est l'impact d'une révocation en cascade ?

  - [ ] Les bonnes pratiques de sécurité
    - [ ] Comment appliquer le principe du moindre privilège dans PostgreSQL ?
    - [ ] Quand utiliser des rôles plutôt que des utilisateurs individuels ?
    - [ ] Comment auditer efficacement les droits d'accès ?