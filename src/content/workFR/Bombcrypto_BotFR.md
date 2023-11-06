---
title: Bombcrypto_Bot
publishDate: 2019-10-02 00:00:00
img: /Portfolio/assets/bombcrypto.jpg
img_alt: Un bot pour gagner des jetons NFT.
description: |
  Un bot pour gagner des jetons NFT..
tags:
  - Python Bot
  - OpenCV
---

### Vue d'ensemble du bot:

Pour comprendre la fonctionnalité et la logique de conception derrière le bot, commençons par une brève présentation du jeu Bombcrypto. Bombcrypto est un jeu "play-to-earn" (joue pour gagner) inspiré du concept classique de Bomberman. Cependant, il se distingue en introduisant une particularité : les joueurs peuvent gagner des BCOIN, une cryptomonnaie en jeu, en brisant des coffres contenant des personnages. Ces personnages sont représentés sous forme de jetons non fongibles (NFT), chacun possédant des caractéristiques de combat distinctes et un identifiant unique. Le jeu fonctionne sur la blockchain, intégrant une IA qui joue au jeu à la place des joueurs. Cette intégration de l'IA devient essentielle car Bombcrypto vise à combiner à la fois le divertissement et la rentabilité, permettant aux joueurs de tirer parti des personnages NFT uniques pour gagner de l'argent.

Étant donné que l'accès au jeu est payant et que l'objectif principal des joueurs est de maximiser leurs gains, les développeurs ont autorisé l'utilisation d'un bot. Cette décision vise à garantir l'équité et à éviter les disparités entre les joueurs qui peuvent lancer activement leurs personnages et ceux qui ont investi dans le jeu mais qui pourraient être occupés ailleurs. De plus, le bot offre la commodité d'être actif même pendant la nuit, garantissant ainsi que les joueurs ne manquent pas de gains potentiels.


### Gameplay :

Alors, quelle est la routine quotidienne d'un joueur Bombcrypto ? Les personnages du jeu disposent de niveaux d'énergie, et pour participer aux activités de destruction de coffres, un personnage doit disposer d'une énergie suffisante. Les joueurs doivent gérer leurs personnages en les envoyant attaquer lorsqu'ils ont de l'énergie et en les rechargeant ou en les mettant au repos lorsque leur énergie est épuisée. Pour ce faire, les joueurs doivent se connecter au jeu. Il est important de garder la fenêtre du jeu active, car les héros ne seront actifs et ne regagneront de l'énergie que lorsque la fenêtre du jeu reste ouverte. Si la fenêtre du jeu est suspendue, même si les héros sont techniquement "actifs", ils ne fonctionneront pas et ne rechargeront pas leur énergie, ce qui les rendra inefficaces. Chaque joueur peut avoir un maximum de 15 personnages dans son équipe.