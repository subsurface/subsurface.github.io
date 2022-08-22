---
layout: page
title: FAQ
lang: fr
permalink: /fr/faq/
ref: faq
---

<style>
p:not(.outside) {margin: 1em 0 1em 2.5rem!important; border-bottom: 1px solid rgba(0,0,0,0.25); padding-bottom: 1rem;}
</style>

<p class="outside">Cette page tente de fournir des réponses à quelques unes des questions les plus fréquentes que nous recevons.</p>

# Général

### Combien coûte Subsurface?
Subsurface est un logiciel open source. Il est gratuit à utiliser (et non, nous ne sommes pas à la recherches de dons). Il est écrit par un groupe de personnes enthousiastes qui font cela durant leur temps libre - en ce compris la mise à disposition du stockage de Subsurface dans le cloud et toute l'infrastructure nécessaire. Veuillez tenir compte du fait que cela implique qu'ils répondront à vos demandes lorsqu'ils en ont le temps, et qu'ils n'apprécient généralement pas d'être considérés comme un service support d'un logiciel commercial. Si vous désirez un carnet de plongée commercial, il y en a beaucoup d'autres disponibles.
### Merci d'ajouter la super fonctionnalité suivante
Comme indiqué pour la question précédente, Subsurface est écrit et maintenu par des volontaires. Il compte également 10.000 utilisateurs. L'éventail actuel est fonctionnalités tend à établir une balance raisonnable entre une expérience utilisateur facile à comprendre, et la rencontre des fonctions les plus souvent demandées. Certaines nouvelles fonctions sont souvent rejetées si aucun des développeurs existants ne trouve pas franchement que cette fonction apporterait quelque chose d'important à la majorité de nos utilisateurs.
### La consommation de gaz (SAC) calculée par Subsurface est erronée
Vous attendez probablement que le calcul de consommation de gaz suive la loi des gaz parfaits. Malheureusement, les gaz réels ne sont pas parfaits. Et Subsurface [tient compte de la compressibilité des gaz](https://thetheoreticaldiver.org/wordpress/index.php/2017/11/02/when-real-gas-corrections-matter/).

# Support des systèmes d'exploitation

## Windows
### Versions supportées
Subsurface fonctionne sous Windows 10 et 11. Il devrait encore fonctionne sous Windows 8 (mais bon, pourquoi voudriez-vous faire tourner ça). Les versions plus anciennes ne sont plus supportées. Veuillez vous référer à la section Windows pour les questions spécifiques au système d'exploitation. 
### Où se trouvent les fichiers log sous Windows?
Les logs sont situé dans le dossier `C:\Users\Home\AppData\Roaming\Subsurface` dans les deux fichiers `subsurface_out.log` et `subsurface_err.log`
### De quels drivers ai-je besoin pour mon ordinateur de plongée
Grande question - généralement ceux qui sont spécifiques à la combinaison de votre ordinateur de plongée et le câble de téléchargement que vous utilisez. Et il est très difficile de donner des réponses universellement correctes.

## macOS
### Versions supportées 
Subsurface fonctionne sur les Macs Intel tournant sous macOS 10.15 ou plus récent. Subsurface fonctionne sur les Macs M1 en mode émulation Rosetta. Veuillez vous référer à la section macOS pour les questions spécifiques à ce système d'exploitation.
### Pouvez-vous publier des applications pour les versions plus anciennes de macOS? 
Apple a cessé de supporter 10.14 et plus ancien. 
### Je n'arrive pas à télécharger depuis mon ordinateur de plongée Bluetooth sur macOS 12 / Monterey
C'est un problème connu; nous travaillons à un correctif, mais pour l'instant la seule solution est de télécharger vers un appareil mobile / Subsurface-mobile et synchroniser votre carnet de plongée en utilisant le Cloud Subsurface.
### Existe-t-il une version native de Subsurface pour les Macs à base d'Apple M1
Plusieurs libraires importantes sur lesquelles est basé Subsurface ne supportent que partiellement les Macs M1. Nous travaillons à une version limitée pour les M1, mais pour l'instant il vaut mieux utiliser les applications Intel.

## Linux
### Versions supportées
Subsurface fonctionne sur la plupart des distributions Linux. Les développeurs maintiennent activement des applications pour les versions actuelles de Fedora, openSUSE et Ubuntu. Il y a aussi une version Snap et une AppImage. En général, essayez d'abord une version spécifique à une distribution. Si cela ne fonctionne pas, essayer la version Snap ou l'AppImage. Veuillez vous référer à la section Linux ce-dessous pour d'autres questions.
### Pouvez-vous ajouter des applications pour ma distribution Linux préférée?
Ajouter le support pour une distribution Linux supplémentaire demande généralement beaucoup de travail et, vu le nombre limité d'utilisateur, a peu de chance de se produire. Mais s'il-vous-plaît, contactez-nous si vous pensez qu'il y a une distribution que nous devrions ajouter à la place des trois que nous supportons actuellement (Fedora, openSUSE, Ubuntu).
### Puis-je compiler ma propre application?
Oui, généralement c'est relativement facile (partant du principe que vous êtes familier avec le développement C/C++ sous Linux). Le fichier `INSTALL` dans le dossier source est le meilleur endroit pour démarrer. Contactez les développeurs si vous avez besoin d'aide au-delà de ça (parce que cela veut probablement dire que nous devons mettre à jour le fichier `INSTALL`...)

## Android
### Quelle est la version minimale requise pour Android?
Actuellement, la version minimale est Android 5.0 (mais beaucoup d'anciennes version d'Android ont d'autres soucis avec Subsurface-mobile, p. ex. avec les certificats SSL utilisés par nos serveurs).
### Depuis quels ordinateurs de plongée Subsurface peut-il télécharger directement sur Android?
Les ordinateurs de plongée Bluetooth et basée sur BLE ainsi que ceux utilisant un USB série devraient généralement fonctionner (à condition d'être complètement supportés par Subsurface, évidemment). Ceux qui ne fonctionnent pas sont les autres périphériques USB (comme USB HID (p. ex. la gamme Suunto EON Steel), le stockage USB  (p. ex., Uemis Zurich), MTP (p. ex., Garmin)).

## iOS
### Depuis quels ordinateurs de plongée Subsurface peut-il télécharger directement sur iOS?
Seuls les ordinateurs de plongée Bluetooth et BLE (qui sont déjà supportés par Subsurface) fonctionnent sur les appareils iOS. Aucun téléchargement par câble n'est possible.

# Problèmes spécifiques à certains ordinateurs de plongée
### Anciens ordinateurs de plongée Suunto
La plupart des câbles de téléchargement sont basés sur FTDI et nécessitent l'installation des drivers appropriés. Certains autres câbles de tierce partie nécessitent d'autres drivers. Sans ces drivers, les ordinateurs de plongée ne s'afficheront pas. Lorsque l'appareil est visible (`COMn` or `/dev/tty...`), si vous avez des erreurs de délai ou de données, consultez la <a href="#i-get-timeouts-or-data-error-when-downloading">question concernant les erreurs de données</a>.
### J'obtiens des erreurs de données ou des délais lorsque je télécharge
Le plus fréquemment, les raisons sont liées à des contacts humides ou sales, ou une batterie faible. Cela n'a pas d'importance si l'appareil s'allume. Le mode téléchargement nécessite souvent un voltage stable plus élevé pour fonctionner. Et malheureusement nous avons même constaté des cas où le logiciel du vendeur fonctionnait (parce qu'il peut faire un bien meilleur travail en 'correction d'erreur'), mais Subsurface ne télécharge pas tant qu'il n'y aura pas une batterie chargée et que les contacts seront vraiment secs et propres.
### Les téléchargements BLE (Bluetooth Low Energy) sont incroyablement lents
Oui, ils le sont. À partir du moment où Subsurface support le téléchargement BLE depuis une grande quantité d'ordinateurs de plongée venant de nombreux fabricants différents, le code n'est généralement pas aussi bien adapté pour un modèle spécifique que ce que l'application du constructeur pourrait faire. En conséquence, ces téléchargements sont horriblement lents. En général, télécharger un petit nombre de plongée est fastidieux, mais pas horrible. Mais un premier téléchargement avec un centaine de plongées ou plus peu prendre une heure ou plus - et parfois il est difficile de terminer le téléchargement sans obtenir des erreurs qui obligent à annuler le téléchargement. Il est vraiment intéressant de télécharger tôt et souvent. Et si l'ordinateur proposer un moyen de télécharger via un câble USB (en plus du BLE, comme par exemple la gamme Suntoo EON Steel), c'est clairement préférable, en particulier lors du premier téléchargement.
## Garmin Descent
### Subsurface-mobile supporte-t-il le Garmin Descent?
Les ordinateurs de plongée Descent sont uniquement supportées sur Windows, macOS, et Linux, et uniquement en téléchargement par câble. Il n'existe aucun projet de support de téléchargement BLE sur une des plateformes.
### Puis-je importer directement les fichiers '.FIT'?
Si pour une raison quelconque vous n'arrivez pas à télécharger normalement, mais avez accès aux fichiers `.FIT`, vous pouvez toujours utiliser Subsurface pour importer (ou mieux, télécharger) ces fichiers. Créez simplement un dossier `...chemin.../Garmin/Activity` et copiez les fichiers `.FIT` dans ce dossier. Démarrez ensuite le téléchargement Subsurface et entrez `...chemin...` (sans le `Garmin/Actity` part) dans le champ Connexion et pressez Télécharger.
### Le Garmin Descent Mk2/Mk2i refuse de se connecter
Le Descent Mk2/Mk2i est une appareil MTP qui cause des soucis occasionnels lorsqu'on tente de télécharger depuis cet appareil vers Subsurface. Le MPT ne supporte qu'une seule connexion; ainsi, les autres applications MTP peuvent empêcher Subsurface de communiquer avec l'ordinateur de plongée. Quittez les applis telles que Android File Transfer.
### Garmin Descent Mk2/Mk2i sous Windows
Vous avez besoin du driver USB adéquat pour communiquer avec le Descent Mk2/Mk2i:<br>- téléchargez [Zadig 2.6](https://zadig.akeo.ie/) et démarrez-le <br>- connectez le Descent et sélectionnez MTP<br>- attendez que Zadig proposer le Descent parmi les options (cela peut nécessitez un cycle brancher/débrancher)<br>- sélectionnez le Descent et demander à Zadig d'installer `libusb-win32` (attendez la fin de cette étape qui prend un certain temps)<br>- débrancher le Descent et rebranchez-le, en sélectionnant à nouveau MTP<br>- Subsurface est maintenant capable de téléchargez (n'entrez rien dans le champ Connexion)

# Autres questions

Si votre question n'est pas abordée ici, veuillez consulter le [Forum utilisateurs](https://subsurface-divelog.org/user-forum/) (utilisez la fonction de recherche) et si vous n'y trouvez aucune réponse, créez un nouveau sujet et demandez de l'aide.

<p class="outside"> Ce FAQ est maintenu sur [GitHub](https://github.com/subsurface/subsurface.github.io) -- les demandes de modifications sont bienvenues.  <p>

***
