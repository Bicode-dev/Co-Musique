# 🎵 Co-Musique

**Votre musique. Celle qui est sur votre disque — et celle que vous voulez
garder.**

Un lecteur audio pour Windows, Linux et Android. Pas de compte, pas
d'abonnement, pas de publicité, pas de télémétrie.

![version](https://img.shields.io/badge/version-1.10.2-8B929C)
![plateformes](https://img.shields.io/badge/Windows%20·%20Linux%20·%20Android-8FA0B5)
![bêta](https://img.shields.io/badge/bêta-à%20tester-F5C542)

> **⚠ C'est une bêta, et j'ai besoin de vous.**
> Elle marche, mais elle n'a tourné que sur une poignée de machines.
> **Cassez-la, et dites-moi ce qui vous agace.**
> → [Comment faire remonter](#-dites-moi-quoi-améliorer) — deux minutes.

---

## Le problème que ça résout

Vous avez de la musique. Elle est éparpillée.

Des MP3 récupérés au fil des années dans un dossier. Des morceaux que vous
n'écoutez que sur YouTube parce qu'ils ne sont sur aucune plateforme. Une radio
que vous mettez le matin. Un podcast pour le trajet. Et pour tout ça : quatre
applications, dont trois veulent un compte et deux vous montrent des pubs.

**Co-Musique met les quatre au même endroit**, sans rien demander en échange.

| Vous avez… | Co-Musique… |
|---|---|
| Des fichiers dans un dossier | les lit, les range par artiste et album, sort les pochettes |
| Un morceau qui n'existe qu'en ligne | le **récupère sur votre disque**, écoutable sans connexion |
| Une radio préférée | 50 000 stations, cherchables par pays et par genre |
| Un podcast | collez le flux RSS, écoutez, gardez des épisodes hors ligne |
| Un lien partagé par un ami | ouvrez-le **dans** Co-Musique, playlist comprise |
| Envie de tout garder chez vous | rien n'est enfermé : ce sont vos fichiers, dans vos dossiers |

---

## Ce qui est agréable dedans

- **« Lire » joue en ligne tout de suite**, sans rien télécharger — et on peut
  avancer dans le morceau. La flèche à côté le garde hors ligne, en MP3.
- **Un accueil qui montre ce qui joue** : la pochette en grand, la progression
  et les commandes, puis vos morceaux au hasard, les ajouts récents, les plus
  écoutés et vos artistes, en images.
- **Sur téléphone, une barre de navigation en verre liquide** : la bulle de
  l'onglet coule d'un onglet à l'autre, et se fait glisser du doigt.
- **Tout ce que vous récupérez est en MP3**, sur PC comme sur téléphone, avec
  son titre, son artiste et sa pochette dans le fichier. Rien à régler.
- **Co-Musique se tait quand Co-Chan lance un anime** (PC) : la musique se met
  en pause dès qu'un épisode démarre. Relancée pendant l'épisode, elle
  continue. Réglages → Lecture pour le désactiver.
- **Le mode mini** (petite fenêtre au-dessus des autres) répond à la barre
  d'espace : un clic dessus, espace, pause.
- **Un panneau des téléchargements** (bouton dans la barre de lecture, avec le
  nombre en pastille) : en cours, en attente, en échec, terminés, chacun avec
  ses boutons. La file survit à la fermeture et demande avant de reprendre.
- **La bibliothèque trie** — artiste, titre, album, durée, ajout récent, plus
  écoutés, écoutés récemment — et l'accueil s'en sert : « Ajoutés
  récemment », « Les plus écoutés », « Jamais écoutés ».
- **Listes en `.m3u`** : export vers `Musique/Co-Musique/Listes`, import de
  `.m3u`, `.m3u8` et `.pls`.

**Vos morceaux restent chez vous, à un endroit que vous connaissez.** Tout vit
dans `Musique\Co-Musique` — sur PC comme sur téléphone, et vous pouvez choisir
un autre dossier (Réglages → Bibliothèque → Dossier des données) : Co-Musique
déplace tout et repart dessus. Un morceau récupéré
arrive là avec sa pochette et ses étiquettes, rejoint votre bibliothèque, et
reste un MP3 ordinaire : copiez-le sur une clé, mettez-le sur un autre
appareil, lisez-le avec autre chose. Désinstallez Co-Musique demain, il y est
toujours.

**Sur téléphone, il trouve tout.** Y compris la carte SD et les dossiers des
autres applications — il interroge l'index du système, celui que consultent les
grands lecteurs, au lieu de fouiller ce qu'il a le droit de voir.

**Partagez vers Co-Musique.** Un lien YouTube, Spotify ou Deezer envoyé depuis
une autre application ouvre directement la bonne page. Les listes de lecture
aussi.
*Précision honnête : l'audio de Spotify et de Deezer ne se récupère pas — il
est chiffré. Ce que Co-Musique lit, c'est la **liste des morceaux**, puis il
retrouve chacun d'eux ailleurs. Ce ne sera donc pas le même enregistrement, et
l'application vous le dit à l'écran plutôt que de vous laisser le découvrir.*

**Le mode mini.** Un bouton, et la fenêtre devient un petit bandeau qui reste
au-dessus des autres pendant que vous travaillez. L'équivalent audio du
picture-in-picture.

**Une minuterie d'arrêt.** « Coupe dans une demi-heure », ou « à la fin de la
piste ». Elle met en pause — elle ne ferme rien : au réveil, vous reprenez
exactement où le silence s'est fait. Sur l'écran de lecture, ou dans les
réglages.

**Une barre de progression qu'on vise.** Passez la souris dessus : une
étiquette annonce l'instant désigné. Cliquez, vous y êtes.

**Le fond de la fenêtre est à vous.** Neuf motifs — halos, aurore, étoiles,
trame, dégradé, relief, blocs, uni, ou la pochette du morceau en cours — avec
un curseur d'intensité. Et si votre machine peine, une bascule coupe tout ce
qui coûte à la carte graphique.

**Sur Android :** notification avec pochette, boutons du casque, écran
verrouillé, et **deux widgets d'écran d'accueil** qui commandent la lecture
sans ouvrir l'application.

**Et le détail qui compte :** l'interface est monochrome par défaut. Gris,
noir, blanc. La couleur vient des pochettes, pas des boutons. (Treize autres
teintes dans les réglages si ça ne vous va pas.)

---

## Installer et tester

### Windows — le plus simple

Téléchargez `comusique-v1.10.2.exe` et lancez-le. Installation dans votre
profil, **aucun droit administrateur**. L'outil de récupération est livré
avec : la partie « En ligne » marche tout de suite.

> Windows affichera un avertissement SmartScreen. C'est normal : le certificat
> de signature est auto-signé — il met mon nom dans les propriétés du fichier,
> mais ne crée pas de chaîne de confiance. Autant le dire franchement.

### Windows — version portable (un seul .exe)

Téléchargez `comusique-v1.10.2-standalone-portable.exe`, posez-le où vous
voulez (une clé USB, par exemple) et lancez-le. Au premier lancement,
Co-Musique demande :

- **Portable** — tout reste dans un dossier caché `.co-musique` à côté du
  fichier : réglages, bibliothèque, téléchargements, outils. Rien dans votre
  profil Windows. On emporte la clé, on retrouve tout.
- **Normal** — la copie se comporte comme la version installée.

Le fichier contient l'application compressée. Il la prépare **à côté de
lui**, dans ce dossier caché, et jamais dans le dossier temporaire de
Windows. Cela prend quelques secondes à la première ouverture d'une version,
puis les lancements suivants sont immédiats. La copie portable se met à jour
toute seule, en remplaçant son `.exe`, sans rien installer.

### Android

Installez `comusique-v1.10.2.apk`. Autorisez l'accès aux fichiers audio quand on
vous le demande : sans ça, Android renvoie une liste vide sans rien dire et la
bibliothèque paraît cassée.

> ⚠ **Si vous avez la 1.2.0 ou la 1.3.1**, désinstallez-la d'abord. Ces deux
> versions étaient signées avec un certificat de test : Android refuse la mise
> à jour par-dessus et affiche « application non installée », sans autre
> explication. Vos morceaux rangés dans `Musique/Co-Musique` survivent à la
> désinstallation. À partir de la 1.3.2, rien à faire.

**Une seconde autorisation vaut le détour**, et Co-Musique vous la propose dans
Réglages → Bibliothèque : « accès à tous les fichiers ». Elle sert à une chose
et une seule — ranger l'index et les pochettes **à côté de votre musique**,
dans `Musique/Co-Musique`, au lieu de l'espace privé de l'application qu'Android
efface à la désinstallation. Vos morceaux, eux, atterrissent dans votre dossier
Musique dans tous les cas. Refusez-la sans crainte : rien ne cesse de marcher.
Il faut relancer l'application après l'avoir accordée.

### Linux

```bash
tar xzf comusique-v1.10.2-linux-x64.tar.gz
cd comusique-v1.10.2-linux-x64
./install.sh          # aucun sudo
```

**Deux dépendances ne sont pas dans l'archive :**

```bash
sudo apt install libgtk-3-0 libmpv2      # Debian / Ubuntu
sudo pacman -S gtk3 mpv                  # Arch
sudo dnf install gtk3 mpv-libs           # Fedora
```

> ⚠ **Sans libmpv, Co-Musique démarre et reste muet, sans message d'erreur.**
> C'est la panne la plus déroutante de la version Linux. Si vous n'entendez
> rien, c'est ça.

---

## Mises à jour

Co-Musique regarde s'il existe une version plus récente au démarrage. Deux cas,
décidés par le numéro :

- **`1.5.x` → `1.5.7`** — un correctif. Recommandé, annoncé par un bandeau
  discret. « Plus tard » suffit, et ne revient pas pour cette version.
- **`1.5.x` → `1.6.0`** — une évolution. **Requise** : c'est par là que passent
  les corrections de sécurité et les changements de format. Un écran occupe
  alors toute la fenêtre au démarrage, avec les notes de version. Trois
  issues, pas une de plus : installer, ouvrir la page des publications, ou
  quitter. Si le réseau manque, l'application se ferme proprement et vous
  revenez quand vous l'avez — ou vous installez à la main depuis la page des
  publications.

L'installation reprend vos réglages, vos favoris et votre bibliothèque. Rien
n'est envoyé nulle part : la vérification lit une page publique, c'est tout.

---

## 🙏 Dites-moi quoi améliorer

**C'est la partie qui m'intéresse le plus.** Le code, je peux l'écrire. Savoir
ce qui vous agace, non.

### Ce qui m'aide vraiment

Trois choses, dans l'ordre d'utilité :

1. **« J'ai voulu faire X et je n'ai pas trouvé comment. »** Le retour le plus
   précieux. Même si la fonction existe : si elle est introuvable, elle est
   mal placée.
2. **« Ça a planté / ça n'a pas joué. »** Ouvrez **À propos → Journal de la
   session → Copier**, et collez-le. Tout y est. Dites juste ce que vous
   faisiez juste avant.
3. **« C'est moche ici. »** Une capture d'écran avec un cercle rouge dessus.
   Ça a déjà servi plusieurs fois, et c'est redoutablement efficace — la
   moitié de cette version vient de captures entourées.

### Ce sur quoi je doute — votre avis compte

- Le thème monochrome par défaut : trop sobre, ou bien ainsi ?
- Faut-il un onglet « Découvrir », pour quand on ne sait pas quoi écouter ?
- Le fondu de fin de piste : utile, ou gadget ?
- Sur téléphone, la barre du bas à cinq onglets : trop chargée ?
- Les neuf motifs de fond : lesquels ne servent à rien ?

### Ce que je sais déjà

Autant ne pas me le signaler trois fois :

- **Pas d'enchaînement sans blanc** entre deux pistes.
- Les étiquettes **M4A/AAC** ne sont pas lues **sur PC** — les fichiers jouent
  très bien, mais s'affichent sous leur nom. Sur Android, le système les lit
  pour nous, donc le problème n'y est plus.
- Une **liste Spotify ou Deezer** partagée est limitée aux **50 premiers
  morceaux** : chacun demande une recherche, et mille en feraient des heures.

---

## Vie privée, en une phrase

Co-Musique n'a **aucun compte**, n'envoie **aucune donnée d'usage**, et les
seules connexions sortantes sont celles que vous déclenchez : une recherche de
radio, un flux RSS que vous ajoutez, un morceau que vous demandez, la
vérification de mise à jour au démarrage.

Vos fichiers ne sont jamais copiés, déplacés ni modifiés. Vos réglages,
favoris et listes vivent dans `Musique\Co-Musique` : une mise à jour ne les
perd pas, une désinstallation ne les efface pas.

Au premier démarrage, Co-Musique affiche ses **conditions d'utilisation** — et
elles sont **modifiables**, ce qui est inhabituel et volontaire : si vous
redistribuez l'application autour de vous, vous devez pouvoir y porter vos
propres règles sans recompiler quoi que ce soit.

---

## Si la récupération en ligne cesse de marcher

Depuis la 1.5.1, la plupart des pannes se corrigent toutes seules : un « 403 »
met yt-dlp à jour et réessaie ; un refus lié aux cookies relance sans eux ;
Deno, le moteur JavaScript que YouTube impose, se télécharge au premier usage.
Sur PC, ffmpeg (qui convertit en MP3) s'installe aussi tout seul au premier
téléchargement : 90 Mo, une seule fois.

Un seul symptôme, une seule cause dans neuf cas sur dix : **erreur 403**.

YouTube change son protocole toutes les quelques semaines, et l'outil doit
suivre. **Réglages → Outil de récupération → Mettre à jour.** Un clic.

Depuis la 1.3.0, Co-Musique a aussi un **second moteur, intégré**, qui prend
le relais tout seul quand le premier bute — et c'est lui qui fait marcher la
partie « En ligne » sur téléphone, où l'outil externe ne peut pas tourner.

Si ça persiste, YouTube vous prend pour un robot : **Réglages → Cookies du
navigateur**, et choisissez celui où vous êtes connecté. Fermez-le d'abord —
Chrome et Edge verrouillent leur base de cookies tant qu'ils tournent.

---

## Questions rapides

**« Ça remplace Spotify ? »** Non, et ce n'est pas le but. Spotify vous prête
un catalogue. Co-Musique lit *votre* musique et vous aide à en garder une copie
qui reste à vous.

**« Il faut créer un compte ? »** Non. Il n'y a pas de compte à créer, nulle
part, jamais.

**« Où vont les morceaux récupérés ? »** Dans `Musique\Co-Musique`, sur votre
disque — téléphone compris. Ce sont des MP3 ordinaires : copiez-les sur une
clé, mettez-les où vous voulez, lisez-les avec autre chose.

**« Ça marche hors connexion ? »** Vos fichiers et tout ce que vous avez
récupéré : oui, entièrement. Les radios et les podcasts non téléchargés :
non, forcément.

**« Mon PC rame, c'est normal ? »** Non, et il y a un réglage pour ça :
**Apparence → Accélération graphique**. Coupée, le décor se fige, la pochette
n'est plus floutée et les ombres disparaissent — c'est ce qui coûte cher.

**« C'est gratuit ? Il y a un piège ? »** C'est gratuit, il n'y a pas de piège,
et il n'y a rien à vendre. C'est un projet personnel que je partage.

---

**Merci d'essayer.** Vraiment — un logiciel que personne ne casse reste
mauvais longtemps.

*Bicode_DEV — même famille que **Co-Craft** (launcher Minecraft) et
**Co-Menu** (la bibliothèque d'applications).*
