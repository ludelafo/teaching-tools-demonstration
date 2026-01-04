---
marp: true
theme: custom-marp-theme
size: 16:9
paginate: true
author: L. Delafontaine, avec l'aide de GitHub Copilot
description:
  Intégrer l'intelligence artificielle dans la rédaction de supports de cours
  complets textuels
url: TODO
header:
  "[**Intégrer l'IA dans la rédaction de supports de cours
  textuels**][contenu-complet-sur-github]"
footer:
  "[**L. Delafontaine**](https://github.com/ludelafo) - [CC BY-SA 4.0][license]"
headingDivider: 6
---

# Intégrer l'IA dans la rédaction de supports de cours textuels

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
- 2023-2026 : Artios + Chargé de cours @ HEIG-VD.

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

## Un retour en arrière...

- Cette présentation fait suite à un précédent contenu que j'ai rédigé intitulé
  [_"Automatiser ses supports de cours à l'aide de fichiers textuels"_](TODO).
- Dans ce contenu, je présentais les outils que j'utilise pour créer des
  supports de cours et des présentations pour mes cours à partir de simples
  fichiers textuels Markdown.
- Afin que tout le monde puisse suivre cette présentation, je vais faire un bref
  rappel des points clés de ce contenu.

## Intégrer l'IA dans la rédaction de supports de cours textuels

<!-- _class: lead -->

## Objectifs (1)

- Présenter les outils que j'utilise pour créer des supports de cours et des
  présentations.
- Expliquer pourquoi j'ai choisi ces outils.
- Expliquer comment ces outils s'intègrent pour automatiser la création et la
  maintenance des documents.

![bg right:40%][illustration-objectifs]

## Objectifs (2)

- Démonstration des outils.
- Présenter quelques diapositives supplémentaires si le temps le permet.

\
\
**Sentez-vous libre de poser des questions à tout moment durant la présentation
!**

![bg right:40%][illustration-objectifs]

## Avertissement

- Les outils/aspects techniques présentés sont efficaces pour moi, avec des
  compétences techniques intermédiaires.
- Ils ne conviennent pas nécessairement à tout le monde/toutes les situations.
- Ils sont présentés à titre d'exemple et d'inspiration.
- Je n'ai aucune pretention d'exhaustivité ou d'objectivité.

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
- Les retours des étudiant.es sont (extrêmement) positifs.

![bg right:34%][illustration-principale]

### Conclusion personnelle (3)

- La simplicité des outils me force à rester simple et bien structurer le
  contenu.
- Après avoir créé 5 cours à partir de 0 en 2.5 ans, je suis convaincu par cette
  approche.
- Plusieurs personnes impliquées dans le processus de réflexion et la mise en
  place (H. Louis, V. Guidoux, M. Ançay). Je ne suis pas arrivé à ça tout seul.

![bg right:34%][illustration-principale]

### Perspectives d'avenir

- Explorer davantage les capacités de GitHub Copilot avec les agents
  d'intelligence artificielle :
  - Pouvoir donner des templates sur lesquels s'appuyer.
  - Demander à générer un contenu spécifique complet (support de cours,
    présentation, diagrammes, etc.).
  - Automatiser encore plus la création et la maintenance des documents.
- Partager et accompagner d'autres enseignant·es dans l'adoption de cette
  approche.

### Aller plus loin : _"Intégrer l'IA dans la rédaction de supports de cours textuels"_

<!-- _class: lead -->

Un contenu dédié à ce sujet est disponible ici : <TODO>.

### Retrouvez le guide dans le document complet

<!-- _class: lead -->

Un guide détaillé est disponible dans [le document
complet][contenu-complet-sur-github] pour vous aider à adopter cette approche
dans vos propres cours.

![bg right w:75%][contenu-complet-sur-github-qr-code]

## Questions

<!-- _class: lead -->

Merci de votre attention ! Est-ce que vous avez des questions ?

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

### Structure de mes cours

- Présentations orales courtes (j'essaie de viser 20 minutes, mais plutôt 30-40
  minutes).
- Redirection des étudiant.es vers le support de cours pour les détails. Permet
  de renforcer l'apprentissage autonome.
- Exercices pratiques en classe (individuels ou en groupe), inclus dans le
  support de cours. Parfois, le support de cours mélange théorie et pratique.
- Quiz pour évaluer la compréhension des concepts clés.
- Discussions et retours pour améliorer continuellement le cours.

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
[contenu-complet-sur-github-qr-code]:
	https://quickchart.io/qr?format=png&ecLevel=Q&size=400&margin=1&text=https://github.com/ludelafo/teaching-tools-demonstration/blob/main/demonstration/README.md
[license]:
	https://github.com/ludelafo/teaching-tools-demonstration/blob/main/LICENSE.md

<!-- Illustrations -->

[illustration-principale]:
	https://images.unsplash.com/photo-1516979187457-637abb4f9353?fit=crop&h=720
[illustration-objectifs]:
	https://images.unsplash.com/photo-1516389573391-5620a0263801?fit=crop&h=720
