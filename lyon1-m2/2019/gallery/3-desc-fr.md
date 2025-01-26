**Visualisation des habitudes d’écoute sur Spotify**

           	

**Résumé du projet : Analyse des habitudes d'écoute et du profil d'auditeur sur Spotify**

**Problème abordé / Besoin répondu :**

 Le projet vise à explorer les données personnelles Spotify pour offrir une meilleure compréhension des comportements d'écoute. Il répond au besoin des utilisateurs de découvrir leurs préférences musicales, tendances d'écoute, et caractéristiques de profil (genres dominants, artistes favoris, variations saisonnières). Les insights personnalisés seront présentés via des visualisations interactives et claires.

 

**Public cible et tâches :**

* **Public principal :**  
  * Utilisateurs réguliers de Spotify souhaitant analyser leurs comportements d'écoute.  
  * Employés Spotify, pour améliorer les recommandations et comprendre les tendances d'écoute.  
* **Tâches principales :**

  o   Identifier les habitudes d'écoute annuelles (genres, artistes, morceaux).

  o   Analyser les tendances temporelles et spatiales (variations saisonnières, moments spécifiques, origines de l’artiste).

  o   Offrir des visualisations interactives adaptées aux préférences des utilisateurs (cartes de chaleur, histogrammes, graphiques circulaires).

   

**Sources de données choisies :**

\-            Demande de données personnelles sur les12 derniers mois :

* **Historique de streaming :** Analyse des morceaux joués, durée d'écoute, moments de la journée, et type d'appareil.  
* **Morceaux écoutés :** Classification des préférences musicales (titre, artiste, genre, mode d'écoute).  
* **Playlists :** Étude des playlists créées pour comprendre la construction des préférences utilisateur.  
* **Spotify Wrapped :** Récapitulatif annuel pour identifier les grandes tendances.

 

\-            API Spotify : Enrichissement des données pour obtenir les genres écoutés.

 

**Organisation :**

* **Moyens de communication :**  
  * Discord pour les discussions quotidiennes.  
  * Emails pour le partage de documents et liens.  
  * GitHub (Issues et Projects) pour gérer les tâches et priorités.  
* **Sessions de travail :**  
  * Réunion hebdomadaire pour faire le point sur les avancées, suivi via un diagramme de Gantt et méthode Scrum.  
* **Rôles dans le groupe :**  
  * Répartition des tâches de manière polyvalente entre les deux membres pour maximiser la collaboration.

 

**Déroulement du projet**

**1\. Phase de mise en place (03/12/2024 \- 10/12/2024)**

* Création du repository GitHub *SpotifyDataViz* et mise en place du projet.  
* Brainstorming pour définir les données et graphiques à exploiter.  
* Rédaction du document de cadrage (objectifs, public cible, tâches, esquisses).  
* Demande des données personnelles Spotify des 12 derniers mois.  
* Mise en place d’un diagramme de Gantt pour suivre les tâches.

**2\. Réception et analyse des données (17/12/2024)**

* Téléchargement des fichiers Spotify (ex. : *StreamingHistory\_music\_X.json*).  
* Analyse et sélection des données pertinentes.  
* Répartition des tâches et intégration de l’API Spotify pour combler les données manquantes.

**3\. Début de création des graphiques (24/12/2024)**

* Conception des premiers graphiques :  
  * *Top 10 artistes* (barres verticales) avec sélecteurs (jour, semaine, mois).  
  * Radar graph pour visualiser les écoutes mensuelles.  
* Développement et mise à jour du diagramme de Gantt.

**4\. Conception avancée des graphiques (31/12/2024)**

* Création de nouveaux graphiques :  
  * Bubble graph des genres musicaux.  
  * Heatmaps (heures, jours et mois d’écoute).  
  * *Top 10 musiques* (barres verticales) et design de l’interface utilisateur.

**5\. Intégration et itérations (07/01/2025)**

* Assemblage des graphiques dans une visualisation unique avec sélecteurs.  
* Développement d’une carte du monde pour mapper les origines des artistes.

**6\. Présentation intermédiaire (14/01/2025)**

* Difficultés d’intégration des heatmaps ajuster la visualisation.  
* Améliorations du radar graph et simplification de l’affichage.

**7\. Présentation finale (21/01/2025)**

* Refonte de l’interface (abandon de Bootstrap, design épuré).  
* Finalisation des graphiques et intégration des sélecteurs utilisateurs.  
* Livraison finale du projet avec un push GitHub et documentation complète.

 

**Problèmes rencontrés**

* **Effectif réduit :** Projet réalisé par deux personnes, limitant l’avancée parallèle.  
* **Manque de temps :** Difficulté à approfondir certaines fonctionnalités.  
* **Conception de l’interface :** Intégration des graphiques plus complexe que prévu.  
* **Mapping manuel :** Collecte manuelle longue des origines des artistes, avec un échantillon réduit.

 

**Ressources utilisées**

* **Bootstrap :** Framework CSS pour une interface responsive (abandonné pour une approche personnalisée).  
* **GeoJSON :** Représentation des données géospatiales pour le mapping des origines des artistes.  
* **CodePen :** Prototypage et test rapide des fonctionnalités.  
* **Git :** Gestion des versions via GitHub pour la collaboration et le suivi.  
* **API Spotify :** Extraction de données complémentaires (genres, artistes, etc.).  
* **Copilot :** génération de code/assistance.

