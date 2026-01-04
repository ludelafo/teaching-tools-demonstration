---
marp: true
theme: custom-marp-theme
size: 16:9
paginate: true
author: L. Delafontaine, avec l'aide de GitHub Copilot
description:
  Automatiser la création et la maintenance de contenus de cours complets à
  l'aide de simples fichiers textuels.
url: https://ludelafo.github.io/teaching-tools-demonstration/01-automatiser-ses-contenus-de-cours-a-laide-de-fichiers-textuels/presentation.html
header:
  "[**Automatiser ses contenus de cours à l'aide de fichiers
  textuels**][contenu-complet-sur-github]"
footer:
  "[**L. Delafontaine**](https://github.com/ludelafo) - [CC BY-SA 4.0][license]"
headingDivider: 6
---

# Automatiser ses contenus de cours à l'aide de fichiers textuels

<!--
_class: lead
_paginate: false
-->

<https://github.com/ludelafo/teaching-tools-demonstration>

<!-- Visualiser le contenu complet sur GitHub [à cette
adresse][contenu-complet-sur-github]. -->

<small>L. Delafontaine, avec l'aide de GitHub Copilot.</small>

<small>Ce travail est sous licence [CC BY-SA 4.0][license].</small>

![bg opacity:0.1][illustration-principale]

<!--

## Plus de détails sur GitHub

<!-- _class: lead --

_Cette présentation est un résumé du contenu complet disponible sur GitHub._

_Pour plus de détails, consulter le [contenu complet sur
GitHub][contenu-complet-sur-github] ou en cliquant sur l'en-tête de ce
document._

-->

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

<small>

**Parcours**

- 2011-2015 : CFC en informatique @ ETML.
- 2015-2019 : BSc en informatique @ HEIG-VD.
- 2020-2024 : Collaborateur Ra&D @ HEIG-VD.
- 2023-2026 : Artios + Enseignement @ HEIG-VD.

**Enseignement**

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

## Un retour en arrière... (1)

- En 2023, la HEIG-VD m'a proposé d'enseigner mon premier cours universitaire.
- Mon premier réflexe a été de me demander comment créer les présentations du
  cours (PowerPoint, Keynote, etc.).
- Dilemme :
  - Diapositives agréables à regarder, mais qui nécessitent beaucoup
    d'explications pour en comprendre le contenu ?
  - Diapositives qui contiennent beaucoup (trop) d'informations afin que les
    personnes puissent réviser par eux-mêmes ?

### _Ceci est une diapositive avec peu de texte_

Épurée...

Agréable à regarder (subjectif)...

Mais difficile à comprendre.

Que retient-on sur le long terme ?

![bg right:40%][illustration-principale]

### _Ceci est une diapositive avec trop de texte_

<div class="two-columns">
<div>

<small>

Elle a pour but de **donner tous les détails nécessaires pour comprendre** le
sujet abordé. Cependant, elle peut être **difficile à lire et à suivre** pour
les personnes qui assistent à la présentation. De plus, l'information est
**difficile à structurer** et à organiser de manière claire. Cela peut entraîner
une **surcharge d'informations** pour les personnes qui assistent à la
présentation, ce qui **peut décourager** de suivre le contenu.

</small>

</div>
<div>

<small>

**Où et comment mettre les détails importants ?** Comment présenter des exemples
de code, des marches à suivre ou encore expérimenter des exercices pratiques ?
Les schémas ? Les exemples ? **Comment garder l'attention ?** Quel est l'intérêt
de la présentation **si je dois commencer à lire tout mon contenu ?**

</small>

Bref, **la présentation devient le support**, ce qui n'est pas idéal.

</div>
</div>

## Un retour en arrière... (2)

- La conseillère pédagogique m'a permis de réfléchir à une autre approche :
  _**"une présentation n'est pas un support de cours"**_.
- J'ai donc décidé d'adopter une approche hybride :
  - Présentations (**courtes !**) pour soutenir l'enseignement oral.
  - Supports de cours (**complets !**) pour étudier/réviser le contenu.

Nouveau défi : comment créer et maintenir (efficacement) deux types de documents
(présentations et supports de cours) sans doubler le travail ? ➡️ Le cœur de
cette présentation.

## Automatiser ses contenus de cours à l'aide de fichiers textuels

<!-- _class: lead -->

## Objectifs (1)

- Présenter les outils que j'utilise pour créer des contenus de cours et des
  présentations.
- Expliquer pourquoi j'ai choisi ces outils.
- Expliquer comment ces outils s'intègrent pour automatiser la création et la
  maintenance des documents.

![bg right:40%][illustration-objectifs]

## Objectifs (2)

- Démontrer l'utilisation de ces outils.
- Présenter quelques diapositives supplémentaires si le temps le permet.

\
**Sentez-vous libre de poser des questions à tout moment durant la présentation !**

![bg right:40%][illustration-objectifs]

## Avertissement

- Les outils/aspects techniques présentés sont efficaces pour moi, avec des
  compétences techniques intermédiaires.
- Ils ne conviennent pas nécessairement à tout le monde/toutes les situations.
- Ils sont présentés à titre d'exemple et d'inspiration.
- Ce que je partage aujourd'hui ne concerne que ma propre expérience et mon
  opinion personnelle sur ce que je considère comme une bonne expérience
  d'enseignement.
- Je n'ai aucune pretention d'exhaustivité ou d'objectivité.

## Choix des outils pour les contenus et les présentations

<!-- _class: lead -->

### Outils classiques (1)

**Large choix d'outils**

- Présentations : PowerPoint, Keynote, Google Slides, etc.
- Contenus de cours : Word, Google Docs, etc.
- Diagrammes : Visio, Draw.io, etc.

Tous connus et utilisés, mais pas très efficaces pour mes besoins.

![bg right:40%][illustration-principale]

### Outils classiques (2)

**Difficultés**

- Mise en page chronophage.
- Difficulté d'automatisation (génération de documents avec la même mise en
  page).
- Difficulté de collaboration (suivi des modifications).
- Demandent des applications spécifiques (`.pptx`, `.docx`, etc.).

![bg right:40%][illustration-principale]

### Basés sur du texte (1)

**Avantages**

- Simples à lire et à éditer (ce n'est que du texte finalement).
- La mise en page n'est pas à gérer (documents et diagrammes).
- Facilité pour collaborer et automatiser.

![bg right:40%][illustration-principale]

### Basés sur du texte (2)

**Grands choix de formats**

- [Markdown](https://fr.wikipedia.org/wiki/Markdown).
- [reStructuredText](https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html).
- [AsciiDoc](https://asciidoc.org/).
- [LaTeX](https://www.latex-project.org/).
- [PlantUML](https://plantuml.com/) (diagrammes).
- [Mermaid](https://mermaid-js.github.io/mermaid/#/) (diagrammes).
- Et bien plus encore...

![bg right:40%][illustration-principale]

### Markdown

- [Markdown](https://fr.wikipedia.org/wiki/Markdown) permet de créer des
  documents structurés.
- Syntaxe simple
  ([voir l'exemple](https://github.com/ludelafo/teaching-tools-demonstration/blob/main/01-automatiser-ses-contenus-de-cours-a-laide-de-fichiers-textuels/01-exemple/README.md)).
- Peut être utilisé pour générer différents types de documents (supports et
  présentations).
- Des extensions existent pour ajouter des fonctionnalités supplémentaires.

![bg right:40%][illustration-principale]

### PlantUML

- [PlantUML](https://plantuml.com/) permet de créer différents types de
  diagrammes (séquence, classes, etc.).
- Principalement pour le domaine informatique mais extensible à d'autres
  domaines.
- Sa syntaxe est, elle aussi, simple
  ([voir l'exemple](https://github.com/ludelafo/teaching-tools-demonstration/blob/main/01-automatiser-ses-contenus-de-cours-a-laide-de-fichiers-textuels/01-exemple/images/diagramme-plantuml.plantuml)).
- Facilement convertible en différents formats (PNG, SVG, etc.).

![bg right:40%][illustration-principale]

### Marp (1)

- [Marp](https://marp.app/) permet de créer des présentations à partir de
  fichiers Markdown
  ([voir l'exemple](https://github.com/ludelafo/teaching-tools-demonstration/blob/main/01-automatiser-ses-contenus-de-cours-a-laide-de-fichiers-textuels/01-exemple/PRESENTATION.md)).
- Permet de générer des présentations en PDF, HTML, etc.
- Supporte les thèmes personnalisés (polices, couleurs, etc.).
- La présentation sous vos yeux a été créée avec Marp !

![bg right:40%][illustration-principale]

### Marp (2)

- Je n'ai pas besoin de me préoccuper de la mise en page.
- Je n'ai qu'à me concentrer sur le contenu.
- Mes besoins sont simples : un titre, du texte, une image illustrative, etc.
- Pas forcément adapté à tous les usages.

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

- Les
  _"[Devcontainers](https://code.visualstudio.com/docs/devcontainers/containers)"_
  permettent de définir un environnement de développement dans un conteneur
  [Docker](https://www.docker.com/).
- Permet d'avoir un environnement de travail avec tous les bons outils avec les
  bonnes configurations.
- Permet d'être efficace rapidement.

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
  [fichier de configuration du conteneur de développement](https://github.com/ludelafo/teaching-tools-demonstration/blob/main/.devcontainer/devcontainer.json).

![bg right:40%][illustration-principale]

## Choix des outils pour la collaboration et la publication

<!-- _class: lead -->

### GitHub

- [GitHub](https://github.com/) est une plateforme de gestion de code source en
  ligne.
- Construite autour de [Git](https://git-scm.com/), ce qui facilite le suivi des
  modifications.
- Espace de travail, de collaboration et de discussions à plusieurs.
- Exemples :
  [Issues](https://github.com/heig-vd-dai-course/heig-vd-dai-course/issues),
  [PRs](https://github.com/heig-vd-dai-course/heig-vd-dai-course/pulls),
  [Discussions](https://github.com/orgs/heig-vd-dai-course/discussions).

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
- Aussi décrit dans un fichier texte
  ([voir l'exemple](https://github.com/ludelafo/teaching-tools-demonstration/blob/main/.github/workflows/main.yml)).

![bg right:40%][illustration-principale]

## Démonstration

<!-- _class: lead -->

_Let's get our hands dirty!_

<small>Il n'est pas impossible que l'effet démo soit présent. Navré pour les
éventuelles erreurs.</small>

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

### Structure du dépôt et workflow de travail

- Une organisation GitHub par cours.
- Arborescence simple et claire.
- Fichiers Markdown pour les supports de cours et les présentations.
- Fichiers PlantUML pour les diagrammes.
- Utilisation des Issues/PRs/Discussions pour la collaboration entre les
  enseignant.es et avec/pour les étudiant.es.
- Je commence toujours par le support de cours, puis je crée la présentation à
  partir de celui-ci.

### Conclusion personnelle (1)

- La source de vérité de mes contenus reste le support de cours.
- Les présentations demandent peu de maintenance (car les détails sont dans le
  support de cours).
- Ne pas devoir faire attention à la mise en page réduit considérablement le
  temps de création et de maintenance des documents.

![bg right:34%][illustration-principale]

### Conclusion personnelle (2)

- GitHub Actions et GitHub Pages me permettent d'avoir accès à mes cours en tout
  temps, n'importe où.
- Cette approche permet à tout le monde de pouvoir apprendre à son rythme et
  selon ses besoins, même lors d'absences.
- Tout est au même endroit.
- Les retours sont (extrêmement) positifs.

![bg right:34%][illustration-principale]

### Conclusion personnelle (3)

- **La simplicité des outils me force à rester simple et bien structurer le
  contenu.**
- Après avoir créé 5 cours à partir de 0 en 2.5 ans, je suis convaincu par cette
  approche.
- Plusieurs personnes impliquées dans le processus de réflexion et la mise en
  place (H. Louis, V. Guidoux, M. Ançay). Je ne suis pas arrivé à ça tout seul.

![bg right:34%][illustration-principale]

### Perspectives d'avenir

- Rédiger un guide complet pour aider d'autres enseignant·es à adopter cette
  approche.
- Partager et accompagner d'autres enseignant·es dans l'adoption de cette
  approche.

### Aller plus loin : _"Intégrer l'IA dans la rédaction de contenus de cours textuels"_

<!-- _class: lead -->

Visualiser le contenu complet sur GitHub
[à cette adresse](https://github.com/ludelafo/teaching-tools-demonstration/tree/main/02-integrer-lia-dans-la-redaction-de-contenus-de-cours-textuels).

<!--
### Retrouvez le guide dans le document complet

<!-- _class: lead --

Un guide détaillé est disponible dans [le document complet][contenu-complet-sur-github]
pour vous aider à adopter cette approche dans vos propres cours.

![bg right w:75%][contenu-complet-sur-github-qr-code]
-->

## Questions

<!-- _class: lead -->

Merci de votre attention ! Est-ce que vous avez des questions ?

## Diapositives supplémentaires

<!-- _class: lead -->

### Alternatives aux outils présentés (1)

**Marp**

- [Slidev](https://sli.dev/) - Pas le souhait de gérer une application web.
- [Reveal.js](https://revealjs.com/) - Écriture en HTML trop verbeuse.
- [Beamer](https://ctan.org/pkg/beamer) (LaTeX) - Trop complexe pour mes
  besoins.
- [Pandoc](https://pandoc.org/) avec des templates spécifiques - Difficile à
  trouver quelque chose d'esthétique.
- [Pleins d'autres encore...](https://gist.github.com/johnloy/27dd124ad40e210e91c70dd1c24ac8c8)

### Alternatives aux outils présentés (2)

**PlantUML**

- [Mermaid](https://mermaid-js.github.io/mermaid/#/) - Intégration avec GitHub
  excellente, mais syntaxe et types de diagrammes qui ne me conviennent pas.
- [Kroki](https://kroki.io/) - Supporte plusieurs langages de description de
  diagrammes, mais PlantUML était amplement suffisant.

### Alternatives aux outils présentés (3)

**GitHub / GitHub Pages**

- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) - Permet
  de créer des sites web documentaires statiques à partir de fichiers Markdown.
  S'intègre parfaitement avec GitHub Pages. Je ne l'ai pas utilisé car je
  voulais profiter de présenter et utiliser toutes les fonctionnalités offertes
  par GitHub. Un outil pour tout gérer, c'est plus efficace.

À nouveau, la simplicité des outils me force à rester simple et bien structurer
le contenu.

### Exemples de cours que j'ai créés

Voici quelques exemples de cours que j'ai créés en utilisant les outils
présentés dans cette présentation (à différents degrés de maturité) :

- [Développement d'applications internet (DAI)](https://github.com/heig-vd-dai-course/heig-vd-dai-course).
- [Programmation serveur 1 (ProgServ1)](https://github.com/heig-vd-progserv-course/heig-vd-progserv1-course).
- [Programmation serveur 2 (ProgServ2)](https://github.com/heig-vd-progserv-course/heig-vd-progserv2-course).
- [Lancez votre minimum viable product (MVP)](https://github.com/heig-vd-mvp-course/heig-vd-mvp-course).
- [Développement de produits médias (DévProdMéd)](https://github.com/heig-vd-devprodmed-course/heig-vd-devprodmed-course).

### Structure de mes cours

- Présentations orales courtes (j'essaie de viser 20 minutes, mais plutôt 30-40
  minutes).
- Redirection des étudiant.es vers le support de cours pour les détails. Permet
  de renforcer l'apprentissage autonome.
- Exercices pratiques en classe (individuels ou en groupe), inclus dans le
  support de cours. Parfois, le support de cours mélange théorie et pratique.
- Quiz pour évaluer la compréhension des concepts clés.
- Discussions et retours pour améliorer continuellement le cours.

### Outils supplémentaires non présentés

- [optipng](http://optipng.sourceforge.net/) pour optimiser les images PNG.
- [jpegoptim](https://github.com/tjko/jpegoptim) pour optimiser les images JPEG.
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
  améliorer mes cours. Ceux-ci sont disponibles publiquement sur GitHub dans les
  différents dépôts de cours.

## Sources

- [Illustration principale][illustration-principale] par
  [Alexander Grey](https://unsplash.com/@sharonmccutcheon) sur
  [Unsplash](https://unsplash.com/photos/assorted-books-on-wooden-table-eMP4sYPJ9x0)
- [Illustration][illustration-objectifs] par
  [Aline de Nadai](https://unsplash.com/@alinedenadai) sur
  [Unsplash](https://unsplash.com/photos/j6brni7fpvs)

<!-- URLs -->

[contenu-complet-sur-github]:
	https://github.com/ludelafo/teaching-tools-demonstration/blob/main/demonstration/README.md

<!-- [contenu-complet-sur-github-qr-code]:
	https://quickchart.io/qr?format=png&ecLevel=Q&size=400&margin=1&text=https://github.com/ludelafo/teaching-tools-demonstration/blob/main/demonstration/README.md -->

[license]:
	https://github.com/ludelafo/teaching-tools-demonstration/blob/main/LICENSE.md

<!-- Illustrations -->

[illustration-principale]:
	https://images.unsplash.com/photo-1516979187457-637abb4f9353?fit=crop&h=720
[illustration-objectifs]:
	https://images.unsplash.com/photo-1516389573391-5620a0263801?fit=crop&h=720
