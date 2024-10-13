1) Projet de Digitalisation d'Ordonnances Médicales
Ce projet est une application web pour la gestion des ordonnances médicales. 
Elle permet aux médecins de créer des ordonnances et de les partager avec les patients et les pharmaciens via un système sécurisé. 
L'application utilise un modèle relationnel pour stocker les utilisateurs, les rôles, les tokens d'authentification (JWT), et les informations des ordonnances et des médicaments.
2) Fonctionnalités
  Gestion des utilisateurs : Inscription, connexion et validation des utilisateurs (administrateurs, médecins, pharmaciens).
  Sécurité : Utilisation de tokens JWT et refresh tokens pour gérer les sessions utilisateurs de manière sécurisée.
  Création et gestion des ordonnances : Les médecins peuvent créer, modifier et envoyer des ordonnances.
  Consultation des ordonnances : Les pharmaciens peuvent consulter les ordonnances via des références uniques ou des QR codes.
  Stockage des médicaments : Chaque ordonnance peut contenir plusieurs médicaments avec leurs dosages et autres informations pertinentes.
3) Installation et Configuration:
    git clone https://github.com/medihebtbessi/ordonnanceDigitaleBackend.git

4) Configurez les propriétés de l'application dans application.properties ou application.yml :
  Configuration de la base de données MySQL.
  Configuration des paramètres de sécurité (JWT, secret keys).

5) Sécurité :
  L'application utilise une architecture basée sur JWT pour sécuriser les endpoints.
    Les utilisateurs doivent être authentifiés pour accéder aux fonctionnalités de gestion des ordonnances et des médicaments.

6) Technologies Utilisées :
  Backend : Java avec Spring Boot
  Base de Données : MySQL
  Sécurité : JWT pour l'authentification et Spring Security pour la gestion des rôles et des permissions.

7) Diagramme de classe :

  [ClassDiag.pdf](https://github.com/user-attachments/files/17355345/ClassDiag.pdf)
