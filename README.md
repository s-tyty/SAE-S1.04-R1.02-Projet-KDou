# Rapport Web - SAE S1.04 & R1.02 : Projet KDou

Ce dépôt héberge le site web statique servant de rapport officiel pour la SAE S1.04 (Création de base de données) et le module R1.02 (Développement d'interfaces web).

Il présente une analyse de données complète de l'entreprise KDou sous la forme d'une interface web.

## Accès au site

Le site est consultable en ligne via GitHub Pages (lien à activer dans les paramètres du dépôt).

## Contenu du rapport

Le site est structuré selon les consignes du projet :

* **Accueil** : Présentation de l'équipe et introduction au contexte KDou.
* **Mission 1 (Étude des données)** : Analyse du contexte, étude critique des données existantes et propositions d'amélioration.
* **Mission 2 (Interface Low-Code)** : Exploitation de la base de données via une interface (Access/Excel), présentation des indicateurs et des requêtes associées.
* **Mission 3 (Analyse SQL)** : Analyse SQL approfondie sur la nouvelle version de la base de données (Produits, Clients, Origines, etc.).
* **Aperçu technique** : Une page dédiée expliquant la réalisation technique de ce site web (architecture, choix CSS, difficultés rencontrées).

## Contraintes techniques respectées

Conformément au cahier des charges R1.02 :

* **100% codé à la main** : Aucun générateur (Wix, WordPress) ou outil WYSIWYG n'a été utilisé.
* **Langages** : HTML5 et CSS3 uniquement.
* **Design** : Site Responsive (adapté pour ordinateurs portables et de bureau) utilisant Flexbox pour la mise en page.
* **Structure** : Utilisation de balises sémantiques, de tableaux, de listes et d'images.
* **Compatibilité** : Testé et validé sur Firefox.

## Structure des fichiers

```text
/
├── index.html        # Page d'accueil
├── mission1.html     # Rapport Mission 1
├── mission2.html     # Rapport Mission 2
├── mission3.html     # Rapport Mission 3
├── meta-rapport.html # Explication du travail Web
├── css/
│   └── style.css     # Feuilles de style
└── img/
    └── ...           # Captures d'écran, schémas de BD, logos

```
