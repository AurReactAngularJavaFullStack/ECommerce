```
est-ce que l 2 c compatible 
```

### En résumé

- **Compatibilité : OK** dès que le store a une chaînette fermée Ø 3‑6 mm.
- **Sécurité : OK** si le store pèse < 3,5 kg (votre modèle est bien plus léger).
- **Matériel requis** : moteur AM43 + adaptateur EU (fourni) + petit hub Zigbee Tuya pour le Wi‑Fi/voix.

Vous pouvez donc acheter ce duo sans risque ; prévoyez simplement une prise USB à proximité et un mini‑hub Zigbee. Besoin d’un lien direct vers un hub ou d’aide pour la mise en service ? Je suis là !

### Verdict rapide

Oui : **le moteur Zigbee d’AliExpress (2ᵉ capture)** est compatible avec le store enrouleur occultant Temu (1ʳᵉ + 3ᵉ capture), parce que :

1. **Le store Temu possède bien une chaînette bouclée** – on la voit à l’étape 6 du schéma de montage.
2. **Le moteur AM43/MOES accepte toutes les chaînettes perlées 3‑6 mm** et fonctionne justement en pinçant cette boucle. ([Aqara](https://www.aqara.com/en/product/roller-shade-driver-e1/?utm_source=chatgpt.com))
3. **Charge maxi 3,5 kg** pour ce moteur, très largement au‑delà du poids d’un store polyester de 60 × 150 cm (≈ 0,8 kg). ([MOES](https://moeshouse.com/products/zigbee-chain-motorized-blinds-motor?srsltid=AfmBOooMu5of60fcVvED8nUj4JjEIRPg9rOQLxJBjaFDmuaKAXw8otLi&utm_source=chatgpt.com), [moescr.com](https://moescr.com/producto/zigbee-smart-diy-motorized-roller-blinds-shades-drive-motor-2mqtt-setup-available-am43/?utm_source=chatgpt.com))

------

#### Points à vérifier avant de commander

| À contrôler                | Détail                                                  | Comment faire                                                |
| -------------------------- | ------------------------------------------------------- | ------------------------------------------------------------ |
| **Chaînette fermée**       | Boucle continue (pas “cordon libre”)                    | Essayez de tirer : si le brin montant tourne en même temps, c’est bon. |
| **Diamètre perles 3‑6 mm** | Standard sur stores Temu                                | Mesurez une perle ; < 1 cm, c’est ok.                        |
| **Espace pour le boîtier** | 4 × 4 cm à droite ou à gauche de l’axe                  | Le moteur se visse ou se colle juste à côté du support de chaînette. |
| **Alimentation**           | Le kit AliExpress est filaire ; adaptateur 8,4 V fourni | Prévoir une prise USB proche ou rallonge.                    |
| **Passerelle Zigbee**      | Obligatoire pour le contrôle à distance                 | Une petite hub Tuya (~10 €) suffit ; après le moteur apparaît dans Smart Life/Alexa/Google. |

------

#### Installation en 3 minutes

1. **Montez le store** avec les clips Temu (sans percer ou en vissant).
2. **Pincez la chaînette** dans la roue crantée du moteur, puis fixez le boîtier au mur avec le double‑face ou 2 vis.
3. **Alimentez et appairez** : dans Smart Life → “Add device → Zigbee blind driver”, maintenez SET + ▼ 3 s pour le mode pairing.
4. **Réglez les butées** (haut/bas) à la télécommande RF ou dans l’app.

```
est-ce que c possible de rendre c rideaux occultants télécommandable 

Pcq à la base ils sont manuel est-ce que c possible par exemple avec le device du 3 ième screenshot ?
```

### Par où commencer ?

1. **Identifier le rail** : U‑Rail (gorges latérales), rail plat, ou simple tringle ?
2. **Mesurer la charge** (poids total du rideau) pour choisir un moteur assez puissant.
3. **Choisir l’alimentation** : batterie rechargeable (pratique en appartement) ou 230 V (plus fiable).
4. Vérifier la **compatibilité domotique** (Tuya, Zigbee, HomeKit, …) si vous voulez l’intégrer à Alexa/Google.

------

### Conclusion

- **Le robot LY‑1609 ne fonctionnera pas** avec vos panneaux plissés ou stores adhésifs ; il lui faut une chaînette en boucle.
- Pour vos rideaux accordéon, le plus simple est d’installer un **rail motorisé latéral** (SwitchBot Curtain ou rail Tuya) ou de remplacer le store complet par un modèle déjà motorisé.
- Comptez **80‑250 €** par ouverture selon la solution.

Si vous précisez le profil exact de votre rail (photo de la tranche ou dimensions), je pourrai vous conseiller un kit précis et où l’acheter près de Chatou.

### Réponse courte

Oui, **on peut motoriser** des rideaux/manchons occultants manuels, mais pas avec n’importe quel moteur : tout dépend du **mode de déplacement** de votre store.

| Produit de vos captures                                      | Type de manœuvre                                             | Compatible avec le robot LY‑1609 (3ᵉ capture) ?              | Solution réaliste                                            |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1ᵉ & 2ᵉ capture – panneaux plissés/accordéon (porte ou cloison) | Ils glissent latéralement dans un rail, sans chaînette ni corde | ❌ Non : le LY‑1609 est conçu pour *enrouler* une chaînette de store‑rouleau, pas pour pousser un rideau | Remplacer le rail par un rail motorisé (ex. Aqara, Bofu, SwitchBot Curtain U‑Rail) ou acheter directement des panneaux plissés motorisés |
| 4ᵉ capture – store plissé adhésif (type « papier nid d’abeille » à tirer par le bas) | Aucune chaînette ; on saisit la barre‑poids                  | ❌ Non : aucun point d’accroche pour le robot                 | Remplacement complet par un store nid d’abeille tubulaire motorisé (Somfy, Zemismart, Ikea Fyrtur, etc.) |
| Robot Wi‑Fi LY‑1609 (3ᵉ capture)                             | Tire une **chaînette à billes** ou un **cordon boucle**      | ✔️ Oui… *si et seulement si* votre store a cette chaînette    | Idéal sur store‑rouleau, stores bateau ou vénitiens *avec* boucle |

------

### Pourquoi le LY‑1609 ne convient pas à vos modèles plissés

Le petit moteur **pince la chaînette** et la fait tourner. Sans chaînette :

1. Il n’a rien à attraper.
2. La course d’un rideau latéral est bien plus longue qu’un tour de chaînette ; le couple demandé n’a rien à voir.
3. Les rideaux plissés autocollants n’ont même pas de barre rigide où fixer un moteur.

*(Spécifications du robot : moteur à friction pour chaîne 3–6 mm, course max ≈ 3 m, batterie 2600 mAh) ([Amazon](https://www.amazon.com/Smart-Roller-Shutter-Curtain-Switch/dp/B0D5YVY7H1?utm_source=chatgpt.com))*

------

### Quelles options pour **motoriser réellement** vos rideaux ?

| Option                                                       | Budget approx.                             | Avantages                                                    | Inconvénients / travaux                                      |
| ------------------------------------------------------------ | ------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **Rail motorisé “U‑Rail” + SwitchBot Curtain 3**             | ≈ 90 € le moteur + nouveau rail (20–40 €)  | Pose rapide, batterie intégrée, pilotable Tuya/Alexa/Google/HomeKit | Il faut que les chariots de votre rideau soient compatibles ou les remplacer. ([SwitchBot EU](https://eu.switch-bot.com/products/switchbot-curtain-3?utm_source=chatgpt.com)) |
| **Rail tubulaire “track & belt” Tuya/Somfy**                 | 120–250 € selon longueur                   | Silencieux, charge plus lourde, positions précises           | Nécessite recouper le rail à longueur, alimentation 230 V ou batterie externe |
| **Remplacer le store plissé par un modèle nid d’abeille motorisé** | 60–150 € la pièce sur Temu/AliExpress/Ikea | Intégré, propre, batterie et télécommande incluses           | Remplacement complet — pas de récupération de l’existant     |
| **DIY : servo + microcontrôleur**                            | 30–50 €                                    | Sur‑mesure, intégration domotique libre                      | Nécessite impression 3D/bricolage, fiabilité limitée         |

------

