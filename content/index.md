---
title: À propos
date: 2025-06-10
id: "20250610093201"
Mise à jour: 2025-07-31
---
---
# Sujet amené

[Voici un petit blog suivant mon voyage au Japon sous un visa vacance-travail de l'été 2025 à 2026 ?](https://pigeonrationel.github.io/chu-pardu/). Il ne s'agit pas tant d'un blog que de mon carnet de voyage personnel que je rend public afin d'avoir une excuse pour écrire et apprendre les bases afin de maintenir un site web.

Juste un p'tit test. Je vais mettre ici mes quelques idées, découvertes et pensées qui popperont, peut-être, dans la prochaine année. Je ne révise pas mon orthographe plus que ça (hein !).

# Site web statique en markdown

J'utilise [*Quartz*](https://quartz.jzhao.xyz/) pour faire ça. C'est un générateur de site web statique qui me permet de puiser directement dans mes fichiers *markdown* que je crée avec *Obsidian*. Comme ça, que ce soit sur un ordinateur ou un cell, je n'aurai jamais besoin de me casser la tête. Hop, un petit `npx quartz sync` après avoir synchronisé mes appareils avec *Syncthing* pour mettre automatiquement à jour le blog qui copie les fichiers depuis mon ordinateur. Tout passe via GitHub, que j'utilise aussi pour *host* ce supposé site web.

![[20250721_172148.jpg|center|500]]
<p style="text-align: center; font-size: 0.7em;">Petit test d'image et de légende ici. Il s'agit d'une installation puisant dans une source de onsen. La vapeur d'eau laisse derrière elle des traces rendant une partie de la forêt et des environs blancs. Calcium, sulfure ?</p>

J'aurais pu utiliser n'importe quel autre programme pour me faciliter la vie sur le court terme, mais sur le long, je n'aurai jamais à me battre avec *Wordpress* pour la mise en page, ni à récrire la même chose deux fois à deux endroits différents. Ou j'aurais pu utiliser une application mobile, mais *hell that*, y a pas de fun dans ça.

## Limites

Gérer les images va devenir l'enfer probablement sur le long-terme. Afin de limiter l'espace, j'ai aussi fini par utiliser un programme (ImageMagick) en ligne de commande afin de convertir la résolution des images à du 500x500 pixels max : `mogrify -resize 500x500 *.jpg`. Comme ça, les images passent en moyenne de 5 mb à 100 kb. Ce n'est pas rien.

Je ne peux pas simplement prendre un tas d'image et les poster comme ça. Il faut que j'inclus chaque image à l'unité en écrivant son nom, sa position sur la page et sa résolution `[[exemple.jpg|centre|500]]`. Pour les personnes voulant regarder les images de plus prêt, ça risque d'être fatiguant comme cela fait aussi en sorte qu'elles sont comme "collées" sur la page. Impossible de cliquer dessus afin d'augmenter la résolution et mieux voir, va falloir zoomer soi-même la page.

Aussi, gérer les vidéos va surement être agaçant, je n'ai pas encore testé.

Clairement, utiliser WordPress m'enlèverait toutes ces limites ou encore me permettrait de les régler sans trop me casser la tête. Je veux cependant absolument un flow de travail qui m'amène à limiter le plus possible les aller-retours entre ce que j'écris sur mon cell, sur mon ordi et ce que je poste comme je n'ai pas envie de me retrouver avec 10 000 versions différentes d'un même écrit.

Pas mal ça. Bonne visite du blog.