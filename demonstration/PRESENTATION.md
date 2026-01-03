---
marp: true
---

<!--
theme: custom-marp-theme
size: 16:9
paginate: true
author: L. Delafontaine, avec l'aide de GitHub Copilot
title: Démonstration d'outils d'enseignement
description: Démonstration de certains des outils que j'utilise pour enseigner.
url: TODO
header: "[**Démonstration d'outils d'enseignement**][support-de-cours]"
footer: "[**L. Delafontaine**](https://github.com/ludelafo) - [CC BY-SA 4.0](https://github.com/ludelafo/teaching-tools-demonstration/blob/main/LICENSE.md)"
headingDivider: 6
-->

# Démonstration d'outils d'enseignement

<!--
_class: lead
_paginate: false
-->

<https://github.com/ludelafo/teaching-tools-demonstration>

[Visualiser ce document sur GitHub (version complète).][support-de-cours]

<small>L. Delafontaine, avec l'aide de GitHub Copilot.</small>

<small>Ce travail est sous licence [CC BY-SA 4.0][license].</small>

![bg opacity:0.1][illustration-principale]

## Plus de détails sur GitHub

<!-- _class: lead -->

_Cette présentation est un résumé du document complet disponible sur GitHub._

_Pour plus de détails, consulter le [document complet sur
GitHub][support-de-cours] ou en cliquant sur l'en-tête de ce document._

## Qui suis-je ?

<div class="one-third-two-thirds-columns">
<div class="center">

**Ludovic  
Delafontaine**

<img src="https://avatars.githubusercontent.com/u/5037444?v=4" alt="Ludovic Delafontaine" width="200" class="rounded">

[Mail](mailto:ludovic.delafontaine@heig-vd.ch) ·
[GitHub](https://github.com/ludelafo) ·
[LinkedIn](https://www.linkedin.com/in/ludelafo/)

</div>
<div>

**Parcours**

<small>

- 2011-2015 : CFC en informatique @ ETML.
- 2015-2019 : BSc en informatique @ HEIG-VD.
- 2020-2024 : Collaborateur Ra&D @ HEIG-VD.
- 2023-2026 : Artios + Chargé de cours @ HEIG-VD.

</small>

**Enseignement**

<small>

- [DAI](https://github.com/heig-vd-dai-course/heig-vd-dai-course) &
  [MVP](https://github.com/heig-vd-mvp-course/heig-vd-mvp-course) @ TIC.
- [ProgServ1](https://github.com/heig-vd-progserv-course/heig-vd-progserv1-course),
  [ProgServ2](https://github.com/heig-vd-progserv-course/heig-vd-progserv2-course)
  &
  [DévProdMéd](https://github.com/heig-vd-devprodmed-course/heig-vd-devprodmed-course)
  @ COMEM.

</small>

</div>
</div>

## Avertissement

- Les outils/aspects techniques présentés sont efficaces pour moi, avec des
  compétences techniques intermédiaires.
- Ils ne conviennent pas nécessairement à tout le monde/toutes les situations.
- Ils sont présentés à titre d'exemple et d'inspiration.
- Ce que je partage aujourd'hui ne concerne que ma propre expérience et mon
  opinion personnelle sur ce que je considère comme une bonne expérience
  d'enseignement.
- Je n'ai aucune pretention d'exhaustivité ou d'objectivité.

## Un retour en arrière... (1)

- En 2023, la HEIG-VD m'a proposé d'enseigner mon premier cours universitaire.
- Mon premier réflexe a été de me demander comment créer les présentations du
  cours (PowerPoint, Keynote, etc.).
- Dilemme :
  - Diapositives agréables à regarder, mais qui nécessitent beaucoup
    d'explications pour en comprendre le contenu ?
  - Diapositives qui contiennent beaucoup (trop) d'informations afin que les
    personnes puissent réviser par eux-mêmes ?

### _Ceci est une diapositive avec trop de texte_

<div class="two-columns">
<div>

Elle a pour but de **donner tous les détails nécessaires pour comprendre** le
sujet abordé. Cependant, elle peut être **difficile à lire et à suivre** pour
les personnes qui assistent à la présentation. De plus, l'information est
**difficile à structurer** et à organiser de manière claire et concise.

</div>
<div>

Cela peut entraîner une **surcharge d'informations** pour les personnes qui
assistent à la présentation, ce qui **peut décourager** de suivre le contenu. Où
et comment mettre les détails importants ? Les schémas ? Les exemples ? Comment
garder l'attention ? **La présentation devient le support.**

### _Ceci est une diapositive avec peu de texte_

Peu d'informations...

Efficace...

Agréable à regarder (subjectif)...

Mais difficile à comprendre.

Que retient-on sur le long terme ?

![bg right:40%][illustration-principale]

## Un retour en arrière... (2)

- La conseillère pédagogique m'a permis de réfléchir à une autre approche :
  _**"une présentation n'est pas un support de cours"**_.
- J'ai donc décidé d'adopter une approche hybride :
  - Présentations (**courtes !**) pour soutenir l'enseignement oral.
  - Supports de cours (**complets !**) pour étudier/réviser le contenu.

Nouveau défi : comment créer et maintenir (efficacement) deux types de documents
(présentations et supports de cours) sans doubler le travail ? ➡️ Le cœur de
cette présentation.

## _Automatiser la création et la maintenance de supports de cours complets à l'aide de simples fichiers textuels : retour d’expérience_

<!-- _class: lead -->

## Objectifs (1)

- Présenter les outils que j'utilise pour créer des supports de cours et des
  présentations.
- Expliquer pourquoi j'ai choisi ces outils.
- Démontrer comment ces outils s'intègrent pour automatiser la création et la
  maintenance des documents.

![bg right:40%][illustration-objectifs]

## Objectifs (2)

- Partager vos retours d'expérience.
- Discuter des alternatives possibles.

**Sentez-vous libre de poser des questions à tout moment durant la présentation
!**

![bg right:40%][illustration-objectifs]

## Choix des outils pour les supports et les présentations

<!-- _class: lead -->

### Outils classiques (1)

**Outils à disposition**

- Présentations : PowerPoint, Keynote, Google Slides, etc.
- Supports de cours : Word, Google Docs, etc.
- Diagrammes : Visio, Draw.io, etc.

![bg right:40%][illustration-principale]

### Outils classiques (2)

**Difficultés**

- Formats binaires (`.pptx`, `.docx`, etc.).
- Difficulté de collaboration (suivi des modifications).
- Mise en page chronophage.
- Difficulté d'automatisation (génération de documents avec la même mise en
  page).

![bg right:40%][illustration-principale]

### Basés sur du texte (1)

**Avantages**

- Simples à lire et à éditer (ce n'est que du texte finalement).
- La mise en page n'est pas à gérer (documents et diagrammes).
- Facilité de collaboration et à automatiser.

![bg right:40%][illustration-principale]

### Basés sur du texte (2)

**Grands choix de formats**

- [Markdown](https://www.markdownguide.org/).
- [reStructuredText](https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html).
- [AsciiDoc](https://asciidoc.org/).
- [LaTeX](https://www.latex-project.org/).
- [PlantUML](https://plantuml.com/) (diagrammes).
- [Mermaid](https://mermaid-js.github.io/mermaid/#/) (diagrammes).
- Et bien plus, voir [Kroki](https://kroki.io/).

![bg right:40%][illustration-principale]

### Markdown

- [Markdown](https://www.markdownguide.org/) permet de créer des documents
  structurés.
- Syntaxe simple ([voir l'exemple](TODO)).
- Peut être utilisé pour générer différents types de documents (supports et
  présentations).
- Des extensions existent pour ajouter des fonctionnalités supplémentaires.

![bg right:40%][illustration-principale]

### PlantUML

- [PlantUML](https://plantuml.com/) permet de créer différents types de
  diagrammes (séquence, classes, etc.).
- Principalement pour le domaine informatique mais extensible à d'autres
  domaines.
- Sa syntaxe est, elle aussi, simple ([voir l'exemple](TODO)).
- Facilement convertible en différents formats (PNG, SVG, etc.).

![bg right:40% w:90%](./exemples/diagramme-plantuml.svg)

### Marp (1)

- [Marp](https://marp.app/) permet de créer des présentations à partir de
  fichiers Markdown.
- Permet de générer des présentations en HTML, PDF, etc.
- Supporte les thèmes personnalisés (polices, couleurs, etc.).
- La présentation sous vos yeux a été créée avec Marp !

![bg right:40%][illustration-principale]

### Marp (2)

- Je n'ai pas besoin de me préoccuper de la mise en page.
- Je n'ai qu'à me concentrer sur le contenu.
- Mes besoins sont simples : un titre, du texte, une image illustrative, etc.
- Possibilité d'ajouter des en-têtes/pieds de page, quelques mises en forme
  particulières, etc.

![bg right:40%][illustration-principale]

## Choix des outils l'édition

<!-- _class: lead -->

### Visual Studio Code

- [Visual Studio Code](https://code.visualstudio.com/) est un éditeur de code
  source.
- Léger, rapide et personnalisable.
- Supporte de nombreux langages de programmation et formats de fichiers.
- Nombreuses extensions disponibles pour ajouter des fonctionnalités
  supplémentaires.

![bg right:40%][illustration-principale]

### _Development containers_

- [Development containers](https://code.visualstudio.com/docs/devcontainers/containers)
  permettent de définir un environnement de développement dans un conteneur
  [Docker](https://www.docker.com/).
- Permet d'avoir un environnement de développement cohérent et reproductible.
- Utile pour éviter les problèmes de configuration entre différentes machines.

![bg right:40%][illustration-principale]

### Extensions utiles

- [Markdown Lint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint),
  [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
  et
  [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  : améliorent l'édition de fichiers Markdown.
- [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)
  : permet de créer des présentations Marp.
- Liste complète dans le
  [fichier de configuration du conteneur de développement](TODO).

![bg right:40%][illustration-principale]

## Choix des outils pour la collaboration et la publication

<!-- _class: lead -->

### Git

- [Git](https://git-scm.com/) est un système de gestion de versions.
- Permet de suivre les modifications apportées aux fichiers.
- Permet de collaborer efficacement sur des projets.
- Utilisé quotidiennement dans le domaine informatique.

![bg right:40%][illustration-principale]

### GitHub

- [GitHub](https://github.com/) est une plateforme de gestion de code source.
- Construite autour de Git.
- Permet d'héberger des dépôts Git.
- Espace de travail et de discussions en ligne.
- Permet de collaborer facilement entre plusieurs personnes.
- Exemples : [Issues](TODO), [PRs](TODO), [Discussions](TODO).

![bg right:40%][illustration-principale]

### GitHub Pages

- [GitHub Pages](https://pages.github.com/) permet de publier des sites web
  directement depuis un dépôt GitHub.
- Permet de publier des documents (supports de cours, présentations, etc.) en
  ligne.
- Accessible en tout temps et depuis n'importe où.

![bg right:40%][illustration-principale]

## Choix des outils pour l'automatisation

<!-- _class: lead -->

### GitHub Actions

- [GitHub Actions](https://github.com/features/actions) permet d'automatiser des
  tâches dans un dépôt GitHub.
- Permet de générer automatiquement des documents à partir de fichiers source
  (Markdown, PlantUML, etc.).
- Aussi décrit dans un fichier texte (voir l'[exemple](TODO)).

![bg right:40%][illustration-principale]

## Intégration avec l'intelligence artificielle

<!-- _class: lead -->

Mon utilisation de l'intelligence artificielle n'est pas extrêmement poussée ni
révolutionnaire, mais voici comment je l'utilise.

### GitHub Copilot (1)

- [GitHub Copilot](https://github.com/features/copilot) est un assistant de
  programmation basé sur l'intelligence artificielle.
- Aide à écrire du code plus rapidement en suggérant des lignes ou des blocs de
  code.
- Intégré dans Visual Studio Code et d'autres environnements de développement.

![bg right:40%][illustration-principale]

### GitHub Copilot (2)

- Au travers de la HEIG-VD, l'accès à GitHub Copilot est offert.
- Plusieurs modèles disponibles gratuitement (j'utilise souvent Claude Sonnet
  4.5).
- Comme tous les documents sont des fichiers textuels, il n'y a aucune
  difficulté à les comprendre et les mettre à jour (pas de mise en page à gérer
  !).

![bg right:40%][illustration-principale]

### GitHub Copilot (3)

- Utile pour générer des contenus, des exemples de code, des structures de
  fichiers, etc.
- Ne remplace pas la réflexion humaine, mais peut accélérer le processus de
  rédaction.
- Je guide le contenu, Copilot me propose des suggestions.
- J'expérimente encore avec les agents.

**Encore en cours d'exploration !**

![bg right:40%][illustration-principale]

## Démonstration

<!-- _class: lead -->

Les diapositives qui suivent contiennent des erreurs pour illustrer
l'utilisation de la suite d'outils présentée.

### Fonctions en JavaScript

Une fonction qui additionne deux nombres a trois paramètres :

1. Le premier chiffre.
2. Le deuxième nombre.

```
function addition(a, b) {
	return a - b;
}
```

L'addition est effectuée.

![bg right:40%][illustration-principale]

## Conclusion

<!-- _class: lead -->

### Outils choisis

- **Markdown** pour les supports de cours et les présentations.
- **PlantUML** pour les diagrammes.
- **Marp** pour les présentations.
- **Visual Studio Code** avec des extensions utiles pour l'édition.
- **Git**, **GitHub** et **GitHub Pages** pour la collaboration et la
  publication.
- **GitHub Actions** pour l'automatisation.
- **GitHub Copilot** pour l'assistance à la rédaction.

### Structure du dépôt

- Une organisation GitHub par cours.
- Arborescence simple et claire.
- Fichiers Markdown pour les supports de cours et les présentations.
- Fichiers PlantUML pour les diagrammes.
- Fichiers de configuration pour GitHub Actions.
- Utilisation des Issues/PRs/Discussions pour la collaboration.
- Publication automatique avec GitHub Pages.

### Conclusion personnelle (1)

- La source de vérité de mes contenus reste le support de cours.
- Les présentations demandent peu de maintenance (car les détails sont dans le
  support de cours).
- Ne pas devoir faire attention à la mise en page réduit considérablement le
  temps de création et de maintenance des documents.

![bg right:37%][illustration-principale]

### Conclusion personnelle (2)

- GitHub Actions et GitHub Pages me permettent d'avoir accès à mes cours en tout
  temps, n'importe où.
- Plusieurs personnes impliquées dans le processus de réflexion et la mise en
  place (H. Louis, V. Guidoux, M. Ançay). Je ne suis pas arrivé à ça tout seul.
- Après avoir créé 5 cours à partir de 0 en 2.5 ans, je suis convaincu par cette
  approche.

![bg right:37%][illustration-principale]

### Conclusion personnelle (3)

- Cette approche permet à tout le monde de pouvoir apprendre à son rythme et
  selon ses besoins, même lors d'absences.
- Les retours des étudiant.es sont (extrêmement) positifs.
- Par contre, le retour sur investissements est assez catastrophique pour le
  moment. 😅 Mais maintenant que c'est là, 💯.

![bg right:37%][illustration-principale]

### Conclusion personnelle (4)

<!-- _class: lead -->

**La simplicité des outils me force à rester simple et bien structurer le
contenu.**

### Perspectives d'avenir

- Explorer davantage les capacités de GitHub Copilot avec les agents
  d'intelligence artificielle :
  - Pouvoir donner des templates sur lesquels s'appuyer.
  - Demander à générer un contenu spécifique complet (support de cours,
    présentation, diagrammes, etc.).
  - Automatiser encore plus la création et la maintenance des documents.
- Partager et accompagner d'autres enseignant·es dans l'adoption de cette
  approche.

## Questions

<!-- _class: lead -->

Merci de votre attention ! Est-ce que vous avez des questions ?

<small>

Retrouvez cette présentation et le document complet publiquement sur GitHub :
<https://github.com/ludelafo/teaching-tools-demonstration>

</small>

## Diapositives supplémentaires

<!-- _class: lead -->

### Exemples de cours que j'ai créés

Voici quelques exemples de cours que j'ai créés en utilisant les outils
présentés dans cette présentation (à différents degrés de maturité) :

- [Développement d'applications internet (DAI)](https://github.com/heig-vd-dai-course/heig-vd-dai-course).
- [Programmation serveur 1 (ProgServ1)](https://github.com/heig-vd-progserv-course/heig-vd-progserv1-course).
- [Programmation serveur 2 (ProgServ2)](https://github.com/heig-vd-progserv-course/heig-vd-progserv2-course).
- [Lancez votre minimum viable product (MVP)](https://github.com/heig-vd-mvp-course/heig-vd-mvp-course).
- [Développement de produits médias (DévProdMéd)](https://github.com/heig-vd-devprodmed-course/heig-vd-devprodmed-course).

### Quiz

TODO

### Outils supplémentaires non présentés

- [optipng](http://optipng.sourceforge.net/) pour optimiser les images PNG.
- [jpegoptim](http://jpegoptim.sourceforge.net/) pour optimiser les images JPEG.
- [Pandoc](https://pandoc.org/) pour convertir entre différents formats de
  documents (Markdown, HTML, PDF, etc.).
- [Kroki](https://kroki.io/) pour générer des diagrammes à partir de différents
  langages de description (PlantUML, Mermaid, etc.).

### Ressources supplémentaires

- Réflexions autour de l'enseignement et des explications des choix de mes
  outils partagées avec un étudiant d'une volée précédente :
  <https://github.com/orgs/heig-vd-dai-course/discussions/180>.
- [Diátaxis](https://diataxis.fr/) - Comment structurer de la documentation
  technique.
- [Johnny.Decimal](https://johnnydecimal.com/) - Système de classification pour
  organiser les fichiers et les projets.
- Je demande régulièrement des retours d'expérience à mes étudiant.es pour
  améliorer mes cours. Ceux-ci sont disponibles publiquement sur GitHub.

## Sources

- [Illustration principale][illustration-principale] par
  [Alexander Grey](https://unsplash.com/@sharonmccutcheon) sur
  [Unsplash](https://unsplash.com/photos/assorted-books-on-wooden-table-eMP4sYPJ9x0)
- [Illustration][illustration-objectifs] par
  [Aline de Nadai](https://unsplash.com/@alinedenadai) sur
  [Unsplash](https://unsplash.com/photos/j6brni7fpvs)

<!-- URLs -->

[support-de-cours]:
	https://github.com/ludelafo/teaching-tools-demonstration/blob/main/demonstration/README.md
[license]:
	https://github.com/ludelafo/teaching-tools-demonstration/blob/main/LICENSE.md

<!-- Illustrations -->

[illustration-principale]:
	https://images.unsplash.com/photo-1516979187457-637abb4f9353?fit=crop&h=720
[illustration-objectifs]:
	https://images.unsplash.com/photo-1516389573391-5620a0263801?fit=crop&h=720
