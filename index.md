---
title: Instructions hébergées en ligne
permalink: index.html
layout: home
---

# Répertoire de contenu

Les démonstrations de ce cours sont basées sur les démonstrations du kit d’accélération [Guide de démonstration et points de discussion.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG).

Il est important de vous familiariser avec les démonstrations avant d’effectuer cette formation. Pour plusieurs labos, vous allez utiliser des exemples de documents et des réunions Teams et e-mails précréés.

- Préchargez tous les exemples de documents [ici](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/tree/master/Resourcefiles).
- Configurez les réunions Teams et les fils d’e-mails en suivant les instructions fournies [ici](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG).
- Familiarisez-vous avec l’expérience interactive que vous trouverez [ici](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/MS-4012_interactive_experience.pdf).

    > **REMARQUE :** le fichier PDF de l’expérience intéractive est téléchargé directement sur l’appareil (dossier téléchargements).

- Consultez la présentation la plus récente [ici](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/MS-4012-ENU-PowerPoint.pptx).

## Description du cours

Explorez le potentiel de transformation de Microsoft Copilot et son impact sur l’efficacité organisationnelle. Conçue pour les cadres et les dirigeants d’entreprise sans licence Copilot, cette expérience explore l’art de la création d’invites efficaces, offre une expérience interactive et montre comment Microsoft Copilot pour Microsoft 365 peut s’intégrer en toute simplicité dans les workflows d’entreprise quotidiens afin de stimuler la productivité et l’innovation.

Les principaux objectifs de cette formation sont les suivants :

- Apprendre à créer des invites efficaces
- Présenter Microsoft Copilot (sur le web) et guider les participants à travers une expérience interactive
- Présenter Microsoft Copilot pour Microsoft 365 - Microsoft Copilot (dans le cadre du travail), Word, Outlook et Teams
- Inviter les participants à télécharger et essayer Microsoft Copilot pour mobile

## Durée de la formation (non finalisé) 

| # | Rubrique                                 | Détails                                                                                          | Temps total      |
|---|---------------------------------------|--------------------------------------------------------------------------------------------------|-----------------|
| 1 | Rédiger des invites effectives dans Copilot pour Microsoft 365 | - Diapositive sur l’art de l’invite <br> - Diapositive sur la création d’une invite <br> - Diapositive sur le labo Copilot | 5-10 minutes    |
| 2 | Microsoft Copilot sur le web          | - Démonstration de Microsoft Copilot (sur le web) <br> - Expérience interactive  <br> - Diapositive sur le partage d’expérience | 35 minutes      |
| 3 | Fonctionnement de Copilot pour Microsoft 365     | - Diapositive sur Microsoft Graph <br> - Version de démonstration de Copilot dans Word, Microsoft Copilot (mode travail), Copilot dans Outlook et Copilot dans Teams <br> - Diapositive des témoignages <br> - Diapositive sur Microsoft Copilot sur mobile | 25 minutes      |
|   |                                       |                                                                                                  | **La durée totale est estimée à 70 minutes** |


Les liens hypertexte vers chaque version de démonstration sont répertoriés ci-dessous.

## Démonstrations

{% assign demos = site.pages | where_exp:"page", "page.url contains ’/Instructions/Demos’" %}
| Démo |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
