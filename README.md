# Parsec Recompiled

Remake jouable dans le navigateur de **Parsec** (Texas Instruments, 1982 — Jim Dramis
et Paul Urbanus), le shoot'em up à défilement horizontal du TI-99/4A.

▶ **[Jouer](https://xavierory76.github.io/parsec-recompiled/)**

Un seul fichier HTML autonome : pas de dépendance, pas de compilation, pas de serveur.
Ouvrez-le, ou installez-le sur iPhone depuis Safari via « Sur l'écran d'accueil ».

## Ce qui est reproduit

- **Résolution 256×192** et les 15 couleurs matérielles du VDP TMS9918A.
- **La séquence exacte d'un niveau**, relevée seconde par seconde sur un
  enregistrement de partie : trois vagues de chasseurs alternant avec trois vagues
  de croiseurs, le tunnel de ravitaillement, puis la ceinture d'astéroïdes.
- **Les messages du bord** découpés en lettres noires dans la bande de sol, avec
  leur minutage d'origine — y compris les 13 secondes de préavis du tunnel.
- **Le son** : reproduction du générateur SN76489 (voies carrées à diviseur 10 bits,
  bruit par registre à décalage 15 bits, volume sur 4 bits).
- **La synthèse vocale** du bord, qui était l'argument de vente de la cartouche.

## Commandes

| Touche | Action |
|---|---|
| ↑ ↓ | Altitude |
| ← → ou 1 2 3 | Vitesse (LIFT 1 à 3) |
| Espace | Tir |
| P | Pause |
| M | Son |

Au doigt : le cache clavier sous la console sert de pavé tactile, et on peut glisser
sur l'écran pour l'altitude.

Deux pièges hérités de l'original : le canon **explose** s'il surchauffe, et il faut
passer en **LIFT 1** avant d'entrer dans le tunnel sous peine de repartir à sec.

## Portée et limites

Ce dépôt ne contient **que du code et des graphismes originaux**. Le jeu a été
reconstruit à partir de comportements observables — captures d'écran d'époque,
analyse image par image et mesures spectrales d'un enregistrement — et non par
désassemblage ou portage du programme d'origine.

Les sprites sont des dessins originaux calés sur les proportions relevées. Les
sources d'origine de Texas Instruments et l'enregistrement vidéo ayant servi de
référence sont volontairement exclus de ce dépôt.

Projet non affilié à Texas Instruments. *Parsec* est une marque de son propriétaire.
