---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cdn.jsdelivr.net/gh/slidevjs/slidev-covers@main/static/SHE_ZiroE0g.webp
# some information about your slides (markdown enabled)
title: Welcome to Slidev
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
presenter: true
---

# LI2S informatique

Formations IT/DevOps

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Appuyer sur espace <carbon:arrow-right />
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---

# Nos formations

En distanciel ou présentiel, support de cours et machines distances pour les travaux pratiques

-  **Docker** - Créer et administrer des conteneurs d'applications
-  **Kubernetes** - Orchestration des conteneurs
-  **Terraform** - Déployer votre infrastructure cloud AWS avec Terraform
-  **Ansible** - Configuer et automatiser la gestion des serveurs
-  **Solaris** - Administrer vos serveurs Solaris et vos clusters avec SunCluster

<br>
<br>

<Link to="8" title="A propos de LI2S informatique"/>

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/features/slide-scope-style
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
layout: two-cols
routeAlias: docker
---

# Docker (2 jours)
Créer et administrer des conteneurs d'applications

-  **Introduction** 
<br>- Architecture de Docker
<br>- Installation
-  **Conteneur** 
<br>- Décription d'un conteneur
<br>- Exécution et cycle de vie d'un conteneur
-  **Image** 
<br>- Déscrition d'une image Docker
<br>- Création d'une image Docker
-  **Volumes** 
<br>- Volumes pour la persistance des données
<br>- Types de volumes Docker

::right::

<br>
<br>
<br>
<br>

-  **Réseau** 
<br>- Architecture et gestion du réseau
<br>- Création de réseau
-  **Applications micro-services** 
<br>- Structure de Docker-compose 
<br>- Gestion d'une application micro-services
<br>


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/features/slide-scope-style
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>


---
layout: two-cols
---

# Kubernetes (2 jours)
Orchestrez vos conteneurs avec Kubernetes
-  **Introduction** 
<br>- Architecture de Kubernetes
<br>- Description des ressources 
-  **Installation** 
<br>- Types d'installation
<br>- Configuration du client
-  **Pods** 
<br>- Création d'application avec des Pods
-  **Scheduler** 
<br>- Gestion des Pods
<br>- Affinités

::right::

<br>
<br>
<br>
<br>

-  **Services** 
<br>- Gestion du trafic réseau
<br>- Types de services
-  **Controleurs** 
<br>- Deployment et DaemonSet
<br>- Jobs et CronJobs
-  **Volumes** 
<br>- Types de volumes
<br>- PersistentVolume et PersistentVolumeClaim
-  **Helm** 
<br>- Installation d'un Chart avec Helm
<br>- Creation et déploiement d'un Chart  

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/features/slide-scope-style
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: two-cols
---

# Terraform (2 jours)
Déployez votre infrastructure 
-  **Introduction** 
<br>- Qu'est ce que l'Infrastructure As Code
<br>- Architecture de Terraform 
-  **Installation** 
<br>- Installation
<br>- Configuration
-  **Les Variables** 
<br>- Déclaration des variables
<br>- Types de variables
-  **Les Provisionneurs** 
<br>- Types de provisionneurs
<br>- Utilisation

::right::

<br>
<br>
<br>
<br>

-  **Les modules** 
<br>- Définition des modules
<br>- Utilisation des modules d'éditeurs
-  **Les Expressions** 
<br>- Expression conditionnelle 
<br>- Les boucles
-  **La Gestion du State** 
<br>- Définition des BackEnds
-  **Les WorkSpaces** 
<br>- Principes
<br>- Configuration  

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/features/slide-scope-style
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: two-cols
---

# Ansible (2 jours)
Orchestrer vos conteneurs avec Kubernetes
-  **Introduction** 
<br>- Définition de l'IaC : Infrastructure as Code
<br>- Architecture 
-  **Installation** 
<br>- Types d'installation
<br>- Configuration
-  **Les commandes Ad Hoc** 
<br>- Utilisation 
-  **Les inventaires** 
<br>- Inventaire statique
<br>- Inventaire dynamique
-  **Les Playbooks** 
<br>- Structure des playbooks


::right::

<br>
<br>
<br>
<br>

-  **Les Rôles** 
<br>- Création de Rôles
<br>- Appels à un rôle
-  **Les variables** 
<br>- Variables de playbook
<br>- Fichiers de variables
-  **Templates** 
<br>- Jinja2
<br>- Le module template  
-  **Les secrets** 
<br>- Création et utilisation

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/features/slide-scope-style
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>



---
transition: fade-out
---
# Tarifs


<html>
<head>
<title>Tarifs</title>
</head>
<body>

E-Learning: Vidéo de formation 
<br>
Coaching: Vidéo de formation + 1h de Visio questions réponses
<br>
Formation: Formation à distance(via Teams), machines à disposition pour les travaux pratiques
<br>

<table border="2" cellspacing="10" cellpadding="20">
    <tr>
      <th>Cours</th>
      <th>E-Learning</th>
      <th>Coaching</th>
      <th>Formation</th>
    </tr>
    <tr>
      <td>Docker</td>
      <td>59 €</td>
      <td>150 €</td>
      <td>450 €</td>
    </tr>
    <tr>
      <td>Kubernetes</td>
      <td>59 €</td>
      <td>150 €</td>
      <td>450 €</td>
    </tr>
    <tr>
      <td>Terraform</td>
      <td>59 €</td>
      <td>150 €</td>
      <td>450 €</td>
    </tr>
    <tr>
      <td>Ansible</td>
      <td>59 €</td>
      <td>150 €</td>
      <td>450 €</td>
    </tr>
  </table>
</body>
</html>

---
transition: fade-out
---

# LI2S informatique

J'ai créé ma société en 1989 pour démarrer mon activité professionnelle.<br>
Les premiers contrats portaient sur le développement, puis du service.<br>
J'ai développé ensuite mon offre de formation, essentiellement autour de Solaris, étant devenu partenaire formation de SunMicrosystems.<br>
A partir de 2015, je me suis orienté vers l'OpenSource, Linux, Docker, Kubernetes, Terraform et Ansible. 


<br>

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/features/slide-scope-style
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
layout: center
class: text-center
---

# Plus d'informations

[Curriculum vitæ](https://www.samir-lakhdari.com) · [GitHub](https://github.com/samir-lakhdari) · [LinkedIn](https://www.linkedin.com/in/lakhdari/)

<PoweredBySlidev mt-10 />

