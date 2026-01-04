---
marp: true
theme: custom-marp-theme
size: 16:9
paginate: true
author: L. Delafontaine, avec l'aide de GitHub Copilot
description:
  Intégrer l'intelligence artificielle dans la rédaction de contenus de cours
  complets textuels
url: https://ludelafo.github.io/teaching-tools-demonstration/02-integrer-lia-dans-la-redaction-de-contenus-de-cours-textuels/presentation.html
header:
  "[**Intégrer l'IA dans la rédaction de contenus de cours
  textuels**][contenu-complet-sur-github]"
footer:
  "[**L. Delafontaine**](https://github.com/ludelafo) - [CC BY-SA 4.0][license]"
headingDivider: 6
---

# Intégrer l'IA dans la rédaction de contenus de cours textuels

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

## Objectifs

- Présenter les outils que j'utilise pour générer et maintenir des contenus de
  cours textuels à l'aide de l'intelligence artificielle.
- Expliquer pourquoi j'ai choisi ces outils.
- Démontrer l'utilisation de ces outils.
- Espace de partage et de retours.

![bg right:40%][illustration-objectifs]

## Avertissement (1)

- Les outils/aspects techniques présentés sont efficaces pour moi, avec des
  compétences techniques intermédiaires.
- Ils ne conviennent pas nécessairement à tout le monde/toutes les situations.
- Ils sont présentés à titre d'exemple et d'inspiration.
- Je n'ai aucune pretention d'exhaustivité ou d'objectivité.
- Mon utilisation de l'intelligence artificielle n'est pas extrêmement poussée
  ni révolutionnaire. Il reste encore beaucoup de potentiel à explorer.

## Avertissement (2)

- Cette présentation fait suite à un précédent contenu que j'ai rédigé intitulé
  [_"Automatiser ses contenus de cours à l'aide de fichiers textuels"_](TODO).
- Dans ce contenu, je présentais les outils que j'utilise pour créer des
  supports de cours et des présentations pour mes cours à partir de simples
  fichiers textuels Markdown.
- Afin que tout le monde puisse suivre cette présentation, je vais faire un bref
  rappel des points clés de ce contenu.

## Comment je crée mes contenus de cours (1)

- Tous mes contenus de cours sont rédigés en
  [Markdown](https://fr.wikipedia.org/wiki/Markdown) (supports + présentations -
  [voir l'exemple](https://github.com/ludelafo/teaching-tools-demonstration/tree/main/01-automatiser-ses-contenus-de-cours-a-laide-de-fichiers-textuels/01-exemple/README.md)).
- Permet de créer des documents structurés en utilisant une syntaxe simple et
  lisible (PDF, HTML, etc.).
- Permet de se concentrer sur le contenu plutôt que la forme.

![bg right:40%][illustration-principale]

## Comment je crée mes contenus de cours (2)

- Les diagrammes sont rédigés avec [PlantUML](https://plantuml.com/)
  ([voir l'exemple](https://github.com/ludelafo/teaching-tools-demonstration/blob/main/01-automatiser-ses-contenus-de-cours-a-laide-de-fichiers-textuels/01-exemple/images/diagramme-plantuml.plantuml)),
  eux-aussi décrits avec du texte.
- Les fichiers textuels sont faciles à lire et à comprendre.
- De plus, ils sont légers, faciles à versionner et à collaborer.

![bg right:40%][illustration-principale]

## Quels sont mes défis

- La création et la maintenance de contenus de cours demandent du temps.
- Je souhaite me concentrer sur la qualité du contenu et non sur la création
  manuelle des documents.
- L'utilisation d'outils d'IA peut m'aider à accélérer le processus de
  rédaction.

![bg right:40%][illustration-principale]

## La force des contenus textuels

Comme tous mes contenus sont textuels (facile à lire et à comprendre) et que je
n'ai pas besoin de mise en forme complexe, je peux utiliser des outils d'IA pour
m'aider à les rédiger plus rapidement et efficacement.

Avoir une source de vérité textuelle me permet de facilement intégrer des outils
d'IA dans mon flux de travail.

Plus les données d'entrée sont structurées et de qualité, meilleurs sont les
résultats (base de l'IA).

## Choix des outils pour l'intégration avec l'intelligence artificielle

<!-- _class: lead -->

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
- Comme tous les documents sont des fichiers textuels, il a aucune difficulté à
  les comprendre et les mettre à jour (peu de mise en page à gérer !).

![bg right:40%][illustration-principale]

### GitHub Copilot (3)

- Utile pour générer des contenus, des exemples de code, des structures de
  fichiers, etc.
- Ne remplace pas la réflexion humaine, mais peut accélérer le processus de
  rédaction.
- Je guide le contenu, Copilot me propose des suggestions.
- J'expérimente encore pas mal.

![bg right:40%][illustration-principale]

## Démonstration

<!-- _class: lead -->

_Let's get our hands dirty!_

<small>Il n'est pas impossible que l'effet démo soit présent. Navré pour les
éventuelles erreurs.</small>

### Contenus de la démonstration

<div class="two-columns">
<div>

1. Présenter Visual Studio Code.
2. Présenter la structure des fichiers.
3. Présenter GitHub Copilot.
4. Présenter le chat intégré.
5. Rédiger un support de cours textuel.
6. Générer la présentation à partir du support de cours.

</div>
<div>

7. Utiliser le fichier
   [`copilot-instructions.md`](https://docs.github.com/en/copilot/how-tos/configure-custom-instructions/add-repository-instructions#creating-repository-wide-custom-instructions-1)
   pour guider les suggestions globales.
8. Utiliser le dossier
   [`instructions`](https://docs.github.com/en/copilot/how-tos/configure-custom-instructions/add-repository-instructions#creating-path-specific-custom-instructions-1)
   pour guider les suggestions sur des fichiers spécifiques.
9. Générer des diagrammes PlantUML.

</div>
</div>

## Conclusion

<!-- _class: lead -->

### Conclusion (1)

- L'intégration de l'IA dans la rédaction de contenus de cours textuels est
  prometteuse.
- GitHub Copilot m'aide à accélérer la création et la maintenance de mes
  documents.
- L'approche textuelle facilite l'utilisation et l'intégration d'outils d'IA.

![bg right:34%][illustration-principale]

### Conclusion (2)

- GitHub Copilot n'est pas parfait et nécessite une supervision humaine.
- Mes expériences de génération de contenus complets avec le chat intégré sont
  mitigées (skill issues?) :
  - Parfois, les générations sont très pertinentes et permettent un gain.
  - Parfois, je dois me battre pour obtenir de bons résultats. Plus simple de
    faire par soi-même.

![bg right:34%][illustration-principale]

### Conclusion (3)

- La transformation du support de cours en présentation n'est pas bonne pour le
  moment, à cause de la mise en page.
- L'inverse serait sans doute plus efficace (générer le support de cours à
  partir de la présentation).
- Je continue à expérimenter et à affiner mon flux de travail, notamment en
  guidant les suggestions avec des fichiers d'instructions.

![bg right:34%][illustration-principale]

### Conclusion personnelle

- J'essaie de trouver le bon équilibre entre automatisation et contrôle de la
  qualité.
- Difficile à suivre les tendances et les nouveautés.
- Difficile de tout générer (qualité, pertinence, skill issues, etc.).
- Crainte de la perte de l'esprit critique et de la créativité dans
  l'utilisation d'outils d'IA...

![bg right:40%][illustration-principale]

### Perspectives d'avenir (1)

- Explorer davantage les capacités de GitHub Copilot avec les agents
  d'intelligence artificielle :
  - Pouvoir donner des templates sur lesquels s'appuyer.
  - Demander à générer un contenu spécifique complet (support de cours,
    présentation, diagrammes, etc.).
  - Automatiser encore plus la création et la maintenance des documents.
- Tester la restructuration d'un cours complet.
- Tester d'autres outils d'IA et comparer les résultats.

### Perspectives d'avenir (2)

- Rédaction d'un guide/document sur l'utilisation de l'IA dans la création de
  contenus de cours textuels et les conclusions.
- Aides et discussions autour de cette thématique avec d'autres enseignant.es
  (comment garder cet esprit critique et créatif ?).

## Questions

<!-- _class: lead -->

Merci de votre attention ! Est-ce que vous avez des questions ?

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
