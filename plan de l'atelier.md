---
title: formations sur le partage et la préservation du code de recherche
sub-title: atelier proposé dans le cadre d'ARDoISE
date: 21042024
author: Damien Belvèze
---


# Pourquoi préserver le code de recherche ?

Enjeu de reproductibilité (distinguer forge et archive)
Gain de temps pour les autres équipes de recherche

=> orienter la formation sur la préservation du code - faire passer du code d'une forge vers HAL puis vers SWH 
Biotools: https://bio.tools/
scicrunch: https://scicrunch.org/resources/data/source/nlx_144509-1/search
approche communautaire

# déroulement de l'atelier

## démonstration
utiliser un [repo sur Github](https://github.com/moranegg/deposit-template) pour le déposer dans SWH
A partir du repo présent sur "GIthub Wonderland App", montrer aux participants comment s'y prendre pour archiver le code et le rendre visible sur HAL

- présentation du repo Github
- rédaction du codemeta.json dans l'interface du codemeta generator, à partir des informations présentes dans le repo (readme, licence, authors/CFF)
- envoi du repo vers Software Heritage
- référencer le code envoyé dans SWH dans HAL en utilisant le codemeta (au moyen du Software-hID, version longue [^1])
- ajouter certains champs qui manquent dans la notice de HAL (voir informations qui ne se trouveraient pas dans le codemeta)
- montrer comment ça se présente dans le CV-HAL

## Mise en pratique

Les doctorants sont amenés à refaire ce parcours avec un repository fictif (bout de code en BASIC)

