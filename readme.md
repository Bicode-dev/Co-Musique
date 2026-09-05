# 🎵 Co-Musique

**Votre musique. Celle qui est sur votre disque — et celle que vous voulez
garder.**

Un lecteur audio pour Windows, Linux et Android. Pas de compte, pas
d'abonnement, pas de publicité, pas de télémétrie.

![version](https://img.shields.io/badge/version-1.2.0-8B929C)
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
| --- | --- |
| Des fichiers dans un dossier | les lit, les range par artiste et album, sort les pochettes |
| Un morceau qui n'existe qu'en ligne | le **récupère sur votre disque**, écoutable sans connexion |
| Une radio préférée | 50 000 stations, cherchables par pays et par genre |
| Un podcast | collez le flux RSS, écoutez, gardez des épisodes hors ligne |
| Envie de tout garder chez vous | rien n'est enfermé : ce sont vos fichiers, dans vos dossiers |

---

## Ce qui est agréable dedans

**Le mode hors ligne est le vrai truc.** Vous cherchez un morceau, vous cliquez
« Écouter ». Il descend sur votre disque avec sa pochette et ses étiquettes,
atterrit dans `Musique\Co-Musique`, et rejoint votre bibliothèque comme
n'importe quel fichier. Dans le train sans réseau, il est là. Si vous
désinstallez Co-Musique demain, il y est toujours — c'est un MP3 ordinaire,
lisible partout.

**Le mode mini.** Un bouton, et la fenêtre devient un petit bandeau qui reste
au-dessus des autres pendant que vous travaillez. L'équivalent audio du
picture-in-picture.

**L'écran de lecture.** Grande pochette, gros boutons, la file à suivre. On
clique la pochette en bas pour l'ouvrir.

**Sur Android :** notification avec pochette, boutons du casque, écran
verrouillé, et **deux widgets d'écran d'accueil** qui commandent la lecture
sans ouvrir l'application.

**Et le détail qui compte :** l'interface est monochrome par défaut. Gris,
noir, blanc. La couleur vient des pochettes, pas des boutons. (Treize autres
teintes dans les réglages si ça ne vous va pas.)

---

## Installer et tester

### Windows — le plus simple

Téléchargez `comusique-v1.2.0.exe` et lancez-le. Installation dans votre
profil, **aucun droit administrateur**. L'outil de récupération est livré
avec : la partie « En ligne » marche tout de suite.

> Windows affichera un avertissement SmartScreen. C'est normal : le certificat
> de signature est auto-signé — il met mon nom dans les propriétés du fichier,
> mais ne crée pas de chaîne de confiance. Autant le dire franchement.

### Android

Installez `comusique-v1.2.0.apk`. Autorisez l'accès aux fichiers audio quand on
vous le demande : sans ça, Android renvoie une liste vide sans rien dire et la
bibliothèque paraît cassée.

### Linux

```bash
tar xzf comusique-v1.2.0-linux-x64.tar.gz
cd comusique-v1.2.0-linux-x64
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
  Ça a déjà servi plusieurs fois, et c'est redoutablement efficace.

### Ce sur quoi je doute — votre avis compte

- Le thème monochrome par défaut : trop sobre, ou bien ainsi ?
- Faut-il un onglet « Découvrir », pour quand on ne sait pas quoi écouter ?
- Le fondu de fin de piste : utile, ou gadget ?
- Sur téléphone, la barre du bas à cinq onglets : trop chargée ?

### Ce que je sais déjà

Autant ne pas me le signaler trois fois :

- Les étiquettes des fichiers **M4A/AAC** ne sont pas lues. Ils jouent très
  bien, mais s'affichent sous leur nom de fichier.
- **Pas d'enchaînement sans blanc** entre deux pistes.
- Le **partage depuis d'autres applications** (YouTube, Spotify, Deezer →
  Co-Musique) n'est pas encore fait. C'est le prochain chantier.

---

## Vie privée, en une phrase

Co-Musique n'a **aucun compte**, n'envoie **aucune donnée d'usage**, et les
seules connexions sortantes sont celles que vous déclenchez : une recherche de
radio, un flux RSS que vous ajoutez, un morceau que vous demandez.

Vos fichiers ne sont jamais copiés, déplacés ni modifiés. Vos réglages,
favoris et listes vivent hors du dossier d'installation : une mise à jour ne
les perd pas, une désinstallation ne les efface pas.

---

## Si la récupération en ligne cesse de marcher

Un seul symptôme, une seule cause dans neuf cas sur dix : **erreur 403**.

YouTube change son protocole toutes les quelques semaines, et l'outil doit
suivre. **Réglages → Outil de récupération → Mettre à jour.** Un clic.

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
disque. Ce sont des MP3 ordinaires : vous pouvez les copier sur une clé, les
mettre sur votre téléphone, les lire avec autre chose.

**« Ça marche hors connexion ? »** Vos fichiers et tout ce que vous avez
récupéré : oui, entièrement. Les radios et les podcasts non téléchargés :
non, forcément.

**« C'est gratuit ? Il y a un piège ? »** C'est gratuit, il n'y a pas de piège,
et il n'y a rien à vendre. C'est un projet personnel que je partage.

---

**Merci d'essayer.** Vraiment — un logiciel que personne ne casse reste
mauvais longtemps.

*Bicode_DEV — même famille que **Co-Craft** (launcher Minecraft) et
**Co-Menu** (la bibliothèque d'applications).*
