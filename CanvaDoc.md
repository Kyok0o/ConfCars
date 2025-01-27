# Cahier des charges - Configurateur de voiture

## Elyas Triki
### 06.01.2024
### IDA-P4B

---

## Sommaire
1. **Matériel et logiciels à disposition**  
2. **Prérequis**  
3. **Descriptif complet du projet**  
   - 3.1 **Résumé général du projet**  
   - 3.2 **Méthodologie**  
   - 3.3 **Description de l’application**  
   - 3.4 **Structure du code**  
   - 3.5 **Planification**  
4. **Consignes et livraisons spécifiques**  
5. **Livrables**  

---

## 1. Matériel et logiciels à disposition

Pour développer cette application web, les technologies suivantes seront utilisées :

- **Visual Studio Code**
- **Windows 10**
- **DBeaver**
- **Suite Office**
- **Serveur web avec PHP**

---

## 2. Prérequis

Le candidat possède les compétences suivantes :

- Conception et création de bases de données MySQL (Modules 105, 153 – 80 heures)
- Création d'un backend en PHP (Modules 307, 133, 151 – 120 heures)
- Création d'un frontend avec HTML5, CSS3 (Module 101 – 80 heures) et JavaScript (ateliers de développement web – ~160 heures)
- Implémentation de la sécurité d’une application (M183 – 40 périodes)

---

## 3. Descriptif complet du projet

### 3.1 Résumé général du projet

Le projet consiste à développer une application permettant aux utilisateurs de configurer une voiture selon leurs préférences. Les fonctionnalités principales incluent :

- Authentification via création de compte ou connexion.
- Personnalisation des véhicules avec ajustement automatique du prix en fonction des options choisies.
- Large choix de modèles, composants et options de personnalisation.

### 3.2 Méthodologie

La gestion du projet suivra une méthodologie adaptée au TPI, au choix du développeur.

### 3.3 Description de l’application

#### Types d’utilisateurs :

1. **Admin**
2. **Client connecté**
3. **Client non connecté**

#### Fonctionnalités disponibles :

**Client non connecté :**

- Voir la liste des voitures modifiables.
- Accéder à une page d'accueil listant les véhicules, avec filtrage par marques.
- Consulter la page d’authentification pour créer un compte ou se connecter.
- Voir une description brève d'un véhicule sans accès aux options de personnalisation.
- Naviguer sur une page listant les pièces de customisation avec filtres.

**Client connecté :**

- Accéder à une page de profil pour consulter ou modifier ses informations.
- Configurer un véhicule avec choix de couleur, options, pièces, etc.
- Voir des offres exclusives et laisser des commentaires sur les véhicules/pièces.

**Administrateur :**

- **Gestion des utilisateurs :**
  - Voir, modifier ou supprimer des utilisateurs.
  - Gérer les rôles.
- **Gestion des véhicules :**
  - Ajouter/modifier/supprimer des véhicules.
  - Configurer les options de personnalisation.
- **Gestion des pièces de personnalisation :**
  - Ajouter/modifier/supprimer des pièces.
  - Gérer leur compatibilité avec les modèles.
- **Gestion des promotions :**
  - Créer et administrer des offres spéciales.

### 3.4 Structure du code

La structure des fichiers suivra une organisation logique et appropriée aux standards enseignés. Cette organisation inclura :

- **Frontend :** Fichiers HTML, CSS, JavaScript.
- **Backend :** Scripts PHP organisés en modules.
- **Base de données :** Scripts SQL pour la gestion des tables.
- **Documentation :** Dossiers pour les guides utilisateur et rapport de projet.

### 3.5 Planification

| Phase              | Durée |
|--------------------|-------|
| Analyse            | 4 h   |
| Implémentation      | 15 h  |
| Test               | 4 h   |
| Documentation      | 9 h   |

---

## 4. Consignes et livraisons spécifiques

- Sauvegarder les sources et données quotidiennement.
- Utiliser Git pour le suivi du projet :
  - Partager avec l'enseignante (droits de clone).
  - Inclure un fichier README avec instructions d'installation.
  - Inclure un jeu de données pour tester les fonctionnalités.
- Maintenir un espace de travail propre.
- Respecter l’horaire fixé.

---

## 5. Livrables

1. **Résumé du TPI** (1 page A4).
2. **Rapport de projet** (livraison intermédiaire et finale).
3. **Code source de l'application** (en annexe).
4. **Manuel utilisateur.**
5. **Journal de travail** (consultable à tout moment).
