```
Comment tu fais tu peux pas mettre un moteur tubulaire électrique le boîtier il est complètement fermé comment tu fais ? 

Pour recharger charger le moteur comment le câble électrique avec prise sort et soit assez long en plus le câble doit être trop long
```

Je vois bien le dilemme : le support latéral (la “platine” blanche fixée au mur) est entièrement fermé ; on se demande comment glisser un moteur tubulaire – et surtout comment faire sortir ou recharger son câble d’alimentation. Voici les solutions les plus courantes, avec leurs avantages, leurs contraintes et la façon de les installer dans la configuration que l’on aperçoit sur tes photos :

------

## 1. Moteur **à batterie intégrée** (Recharge ponctuelle)

| Pour qui ?                | Si tu ne veux **aucun câble apparent** au quotidien.         |
| ------------------------- | ------------------------------------------------------------ |
| Principe                  | Le moteur renferme une batterie Li-ion (autonomie 6 – 12 mois selon l’usage). Pour recharger : tu branches un petit cordon USB-C ou Jack 12 V 1 à 2 fois/an, comme un téléphone. |
| Installation dans ton cas | 1. **Dévisser le cache-platine** (2 vis cruciformes en haut et en bas) → le support s’ouvre, tu retires la barre. 2. **Mesurer le diamètre intérieur** du tube (ø 25 mm, 28 mm ou 38 mm sont les plus courants) et la longueur utile. 3. **Choisir le kit moteur + bagues d’adaptation** correspondant (Somfy WireFree / Zigbee, Tuya, A-OK, etc.). 4. **Glisser le moteur dans le tube**, remettre la goupille côté opposé. 5. Reposer la barre dans le support, refermer la platine. 6. **Quand la batterie est faible**, tu décroches uniquement le côté moteur, tu branches le petit chargeur (ou tu laisses un câble de secours enroulé derrière le rideau). |
| À prévoir                 | Penser à un **chargeur 2 A** et à un **pont domotique** si tu veux piloter via appli (ex. Zigbee / Wi-Fi). |

------

## 2. Moteur **filaire basse tension** (12 V / 24 V)

| Pour qui ?   | Si tu veux éviter les recharges mais garder une basse tension facile à dissimuler. |
| ------------ | ------------------------------------------------------------ |
| Principe     | Le moteur sort avec un **cordon fin (2 conducteurs) de ~2 m**. Ce câble se raccorde à un mini-alimentation 12 V ou 24 V cachée derrière un meuble ou dans une goulotte. |
| Installation | Identique à la batterie, sauf qu’il faut : 1. **Percer un mini-passage** (6 mm) dans la platine ou utiliser le **détrompeur déjà présent** (souvent un opercule) pour faire sortir le câble. 2. **Coller une micro-goulotte** blanche le long du montant de la fenêtre jusqu’à la prise. 3. Brancher l’alim ou un injecteur PoE 24 V si tu veux un seul câble réseau + alim. |
| Avantages    | Pas de recharge, câble discret, aucune manipulation saisonnière. |
| Inconvénient | Légère contrainte esthétique ; il faut une prise proche ou tirer un câble plus long. |

------

## 3. Moteur **filaire 230 V** (classique)

| Pour qui ?   | Si l’ouverture du rideau est lourde, usage intensif, ou si tu disposes déjà d’une arrivée 230 V au-dessus de la baie. |
| ------------ | ------------------------------------------------------------ |
| Principe     | Le câble 4 conducteurs (Phase, Neutre, Terre, Montée/Descente) sort côté moteur, longueur ~2,5 m. On le raccorde à un inverseur mural ou à un module radio 230 V (Somfy RTS, Zigbee DIN, Shelly, etc.). |
| Installation | 1. Même démontage du support. 2. Percer l’orifice pour le câble (Ø 8–10 mm). 3. Descendre dans une goulotte ou dans le doublage placo jusqu’à la sortie 230 V. 4. Poser un **inverseur encastré** (ou un micro-module radio derrière une plaque). |
| Avantages    | Aucune recharge, puissance élevée.                           |
| Inconvénient | Travaux électriques + goulottes plus grosses ; nécessite la terre ; pas toujours esthétique dans un appartement. |

------

### Points clés pour **ouvrir le boîtier** que tu montres

1. Les deux petites vis visibles en façade (haut/bas) retiennent simplement **un couvercle** ; une fois retiré, la platine s’écarte et tu peux **sortir la barre**.
2. Si la barre est télescopique, retire d’abord le **cache-embout** (il est juste emboîté) puis coulisse la partie intérieure pour dégager de la place.
3. Le moteur remplace l’**embout originel** ; le “côté fixe” reste tel quel, l’autre extrémité reçoit l’arbre du moteur + la couronne d’entraînement.

------

## Astuces pour ne pas voir le câble

- **Goulotte de 12 × 7 mm** autocollante (type Legrand ou Schulte-Elektro) peinte en blanc : pratiquement invisible derrière un voilage.
- **Passage dans l’angle mur/plafond** derrière la retombée du rideau.
- **Alimentation solaire** (petit panneau 5 V collé côté extérieur de la vitre) pour les moteurs basse-tension : plus de câble secteur du tout.

------

### En résumé

- **Oui, c’est faisable** même avec un support “fermé” : il suffit de le dévisser, le moteur prend la place de l’embout.
- **Choisis d’abord le type d’alimentation** (batterie intégrée / 12 V / 230 V) en fonction de ta tolérance aux câbles et aux recharges.
- **Prends la bonne taille** (diamètre et couple) ; la plupart des voilages se contentent d’un moteur 1 Nm, Ø 25 mm.
- **Prépare la sortie de câble** : percer l’opercule du support ou laisser la fente prévue et poser une mini-goulotte.

Si tu hésites encore entre batterie ou filaire, dis-moi la **hauteur** de ton rideau, la **fréquence d’ouverture** et si tu as une prise proche : je pourrai t’aider à choisir le modèle le plus simple à installer.