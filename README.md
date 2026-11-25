# ArcheAge Chronicles en français

Traduction française **non officielle** et **complète** d'ArcheAge Chronicles : quêtes, dialogues,
cinématiques, interface, objets, compétences, tutoriel, notes à lire, décor… soit 55 329 lignes.

Elle ne modifie aucun fichier du jeu : elle ajoute seulement un fichier à côté.
Elle fonctionne sous **Windows, Linux et Steam Deck**.

Guide d'installation illustré sur Steam : **[Jouer à ArcheAge Chronicles en français](https://steamcommunity.com/sharedfiles/filedetails/?id=3842833494)**

<!-- Ajouter ici 2 ou 3 captures d'écran du jeu en français (glisser les images dans l'éditeur GitHub). -->

## Télécharger

**[Dernière version](https://github.com/alec1885/archeage-chronicles-fr/releases/latest)** : le fichier `.zip` en bas de la page.

Le nom du zip indique la build du jeu prévue (par exemple `build26912079`).

## Installer

1. Fermez le jeu.
2. Dans Steam, faites un clic droit sur ArcheAge Chronicles, puis **Gérer › Parcourir les fichiers locaux**.
   Sur Steam Deck, passez en mode Bureau pour cette étape.
3. Ouvrez le dossier `X5`, puis le dossier `Content`.
4. Copiez-y le dossier **`Localization`** du zip.
   - Si on vous demande quoi faire d'un dossier qui existe déjà, choisissez **Fusionner** (ou « Écrire dans »).
   - Si on vous demande de remplacer `String.locres`, acceptez : c'est l'ancienne version de la traduction.

   Le fichier doit se retrouver ici :
   `ArcheAge Chronicles\X5\Content\Localization\String\fr\String.locres`
5. Dans Steam, faites un clic droit sur le jeu, puis **Propriétés › Général**.
   Dans **Options de lancement**, écrivez :
   ```
   -culture=fr
   ```
   Si la case contient déjà quelque chose, ajoutez `-culture=fr` à la fin, après un espace
   (et après `%command%` s'il y est).
6. Lancez le jeu : il est en français.

Si le jeu démarre quand même en anglais, ouvrez dans le jeu **Options › General** et choisissez la langue **français**.

## Après une mise à jour du jeu

Quand une mise à jour du jeu modifie des textes, les lignes concernées s'affichent en **coréen**
jusqu'à la version suivante de la traduction. Tout le reste reste en français, et rien ne casse.
Pour mettre la traduction à jour, téléchargez la dernière version et refaites l'étape 4.

## Désinstaller

1. Supprimez le dossier `X5\Content\Localization\String\fr`.
2. Retirez `-culture=fr` des options de lancement.

## Un texte bizarre ou en coréen ?

Vu le nombre de textes à traduire (plus de 21 000 lignes de dialogue à elles seules), la traduction
a été écrite en grande partie par une IA, Claude (d'Anthropic), puis testée en jeu. Il reste donc
sûrement des maladresses.

**Toute aide est la bienvenue** : vocabulaire, lore, noms officiels (canon) des personnages et des
lieux, ou tout texte bizarre à signaler. Ouvrez un [ticket](https://github.com/alec1885/archeage-chronicles-fr/issues)
avec une capture d'écran, ou laissez un commentaire sur le [guide Steam](https://steamcommunity.com/sharedfiles/filedetails/?id=3842833494) de la traduction.

## Merci

Cette traduction n'aurait pas été possible sans le travail des traducteurs russes :

- [ColdVision](https://github.com/ColdVision/ArcheAge-Chronicles-russian-translate) :
  traduction russe, outils et données des objets ;
- [th0masi](https://github.com/th0masi/archeage-chronicles-ru) : traduction russe, qui a permis
  de retrouver les textes anglais officiels ;
- clarkkent : traduction russe, dont l'installateur nous a fourni le texte coréen officiel des
  premières mises à jour du jeu.

## Avertissement

Projet de fans, gratuit, sans lien avec les développeurs ni l'éditeur d'ArcheAge Chronicles.
Le jeu ne prévoit pas officiellement de modifications : vous utilisez cette traduction à vos
risques. Elle a été testée en jeu pendant plusieurs jours sans aucun problème.

## Aux développeurs d'ArcheAge Chronicles

Si vous passez par ici : toute cette traduction est à votre disposition, librement, si elle peut
accélérer une traduction française officielle. Le fichier `String.locres` du zip s'utilise tel quel
(mêmes clés que le jeu), et je peux vous fournir les fichiers de travail (tableaux clé / texte) sur
demande. Aucun besoin de me créditer dans le jeu. Pour me contacter, ouvrez simplement un ticket ici.

**To the ArcheAge Chronicles developers:** this whole translation is freely available to you if it
can help speed up an official French localization. The `String.locres` in the zip can be used as is
(same keys as the game), and I can share the working files (key / text tables) on request.
No credit needed in the game. To reach me, just open an issue on this repository.
