---
title: Newbie sur la Jamstack...
date: 2016-12-20 11:56:00 +01:00
tags:
- jamstack
- jamstatic
- netlify
- DNS
- sous-domaine
layout: post
---

![Roadmap - jamstatic-fr 2016-12-20.png](/uploads/Roadmap%20-%20jamstatic-fr%202016-12-20.png)

Sous le regard bienveillant de <span class="h-card">[Bertrand Keller](https://bertrandkeller.info/)</span>, je délaisse momentanément [mes recherches d'activation de certificats SSL sur Gandi](http://ducamp.me/2016-355)... 

![Netlify-UI.png](/uploads/Netlify-UI.png)

Premiers pas dans l'interface-utilisateur de [Netlify](http://netlify.com/) pour m'essayer à la [JAMstack](http://jamstack.org/fr/) en 2017...

>  La <dfn>JAMstack</dfn> est une manière idéale de bâtir des sites et des applications web performants, sécurisés et simples à mettre à jour.

> **JAM** signifie JavaScript, APIs and Markup (JavaScript, APIs et balisage). C'est l'association de technologies qui progresse le plus rapidement quand il s'agit de bâtir des sites et des applications web : plus de serveurs, hébergez tout votre partie cliente sur des CDNs et utilisez des APIs pour les parties dynamiques. (...)

Premier bénéfice escompté à cette heure : dire [adieu au protocole FTP](https://fr.wikipedia.org/wiki/File_Transfer_Protocol)...

## Paramétrage technique dans l'interface chez Gandi (nom de domaine)

Parcouru rapidement la [notice officielle de configuration d'un sous-domaine](https://www.netlify.com/docs/custom-domains/) que j'étudierai plus tard. 

![Netlify-dns-records.png](/uploads/Netlify-dns-records.png)

À cette heure, j'ai simplement remplacé une ligne dans l'interface-utilisateur de réglages DNS chez Gandi  :

`christophe 10800 IN CNAME christopheducamp.github.io.` est devenu  `christophe IN A 104.198.14.52` 

Plus qu'à attendre la propagation des DNS (quelques heures) pour m'essayer à l'installation d'un SSL, aux plugins jekyll et ajouter les services workers dans Netlify.

Très envie d'apprendre ce monde merveilleux durant les fêtes.

Merci Bertrand.
