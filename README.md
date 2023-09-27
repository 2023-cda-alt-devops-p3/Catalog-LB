# Catalogue-LB

<h2>Diagrammes UML :</h2>

<b>Diagramme de cas d'utilisation (Use Case Diagram)</b><br>
<b>Diagramme de classe (Class Diagram)</b><br>
<b>Diagramme d'objet (Object Diagram)</b><br>
Diagramme de séquence (Sequence Diagram)<br>
Diagramme de collaboration (Collaboration Diagram)<br>
Diagramme d'état (State Diagram)<br>
Diagramme d'activité (Activity Diagram)<br>
Diagramme de composants (Component Diagram)<br>
Diagramme de déploiement (Deployment Diagram)<br>
Diagramme de communication (Communication Diagram)<br>
Diagramme de timing (Timing Diagram)<br>
Diagramme de packages (Package Diagram)<br>
Diagramme de sous-système (Subsystem Diagram)<br>

 <h2>MERISE: </h2>

<b>Modèle conceptuel des données (MCD)</b><br>
<b>Modèle logique des données (MLD)</b><br>
<b>Modèle physique des données (MPD)</b><br>
Diagramme de flux de données (DFD)<br>
Diagramme de flux de processus (PFD)<br>
Diagramme de flux externe (EFD)<br>
Diagramme entité-association (EA)<br>

<b>Diagramme de cas d'utilisation (Use Case Diagram):</b> Il représente les interactions entre les acteurs (utilisateurs ou systèmes externes) et les fonctionnalités d'un système, montrant comment les acteurs utilisent le système pour atteindre leurs objectifs.

<b>Diagramme de classe (Class Diagram):</b> Il illustre la structure statique d'un système en mettant en évidence les classes, les attributs, les méthodes et les relations entre les classes.

<b>Diagramme d'objet (Object Diagram):</b> Il représente des instances spécifiques (objets) de classes à un instant donné, montrant leurs attributs et leurs relations à un moment précis.

<b>Modèle conceptuel des données (MCD):</b> Il décrit les entités, les attributs et les relations entre les données dans un système, fournissant une vue conceptuelle de la structure des données.

<b>Modèle logique des données (MLD):</b> Il transforme le MCD en une représentation plus détaillée en utilisant des concepts de bases de données relationnelles, notamment les tables, les clés primaires, les clés étrangères et les contraintes.

<b>Modèle physique des données (MPD):</b> Il concrétise le MLD en définissant précisément la structure de la base de données, y compris les tables, les colonnes, les types de données, les contraintes, etc., pour une implémentation dans un système de gestion de base de données.

--

Critères d'évaluation

Git
Versionné régulièrement et de manière atomique (Plusieurs "commit" par jour pendant toute la durée du projet) => Vérif Git
Historique de commit propre => (éviter les doublons, les commits inutiles)
Mise en plance d'une branche de développement supplémentaire, voire plusieurs selon l'architecture du site => Vérif sur Git
Fonction "pull request" => Check sur Github
Mise en place un Github Action (automatisation de tests intégration, vulnérabilité, ...) => Check sur Github

Sécurité
Prévenir les vulnérabilités principales (cross site, injection sql, protection des tokens, validation des données) => GoogleSearchConsole, Sucuri
Respect de la protection des données (RGPD, encapsulation)
Utilisation des chemins absolus

SEO
Mise en place de la stratégie SEO : données structurées, ...
PWA (Progressive Web App) : services workers (microphone, localisation, ...)
HTML sémantique

Performance
Bon résultat sur PageSpeed Insights
Optimisation images (surtout mobile)
Limiter le nombre de requêtes

Accessibilité
Accessibilité : title, aria-label, alt
Optimisation des images : poids et formats adaptés
Fournir un site web avec une bonne expérience utilisateur
Texte lisible : interlinéage suffisant, taille des polices proportionnelles, contraste des couleurs optimale, ...

Architecture
Bons principes de structuration respectés, y compris pour le web mobile => vérif des balises (body, header, navbar), et des noms de classes CSS, variables, media queries
Eviter les répétitions en utilisant des fonctions => check du code source

Contenu
Contenu vérifié : informations croisées, résumé de plusieurs sources, ...
Détail des étapes pour chaque diagramme

UI/UX
Features d'animations, transitions, barre de navigation => vérif du site
Design cohérent (couleur, forme, police)