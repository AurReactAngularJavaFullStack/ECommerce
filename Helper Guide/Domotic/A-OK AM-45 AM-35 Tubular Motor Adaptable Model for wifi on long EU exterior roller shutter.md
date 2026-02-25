#### À retenir

- **AM45-20/17 E** ET **AM35-10/17 QE** ➜ radio **433 MHz uniquement** → pas d’appli mobile sans passerelle.
- La lettre **“W”** dans la référence A-OK = **Wi-Fi Tuya intégré** (pas besoin de pont).
- Les adaptateurs US → EU règlent juste le format de fiche ; la tension 230 V est déjà acceptée.

Si tu veux le schéma d’appairage pas-à-pas du pont RF → Wi-Fi ou d’autres liens produits (pont Tuya, RF Bridge, modules DIN), dis-le moi !

### Commandable via appli mobile ?

| Modèle A-OK                                   | Radio intégrée                | Wi-Fi natif         | Contrôle direct par smartphone           | Comment faire si pas Wi-Fi                                   |
| --------------------------------------------- | ----------------------------- | ------------------- | ---------------------------------------- | ------------------------------------------------------------ |
| **AM45-20/17 E** (Ø 45 mm / 20 Nm)            | ✅ 433,92 MHz (protocole A-OK) | ❌                   | **Non** → télécommande 433 MHz seulement | Ajouter un **pont RF-→-Wi-Fi Tuya** ou un **Sonoff RF Bridge** pour piloter l’ouverture depuis Smart Life / eWeLink. |
| **AM35-10/17 QE** (Ø 35 mm / 10 Nm)           | ✅ 433,92 MHz                  | ❌                   | **Non**                                  | Même solution : passerelle RF-Wi-Fi ou module mural Shelly/Sonoff. |
| **AM45-20/17 MEL-W** (la version « W » Wi-Fi) | ✅ 433 MHz                     | ✅ Tuya / Smart Life | **Oui** – appli sans hub                 | —                                                            |

> Ces deux versions “E” et “QE” sont donc **radio uniquement** ; pour avoir le contrôle mobile, il faut soit acheter la déclinaison **“MEL-W”** (Wi-Fi natif), soit rajouter une **passerelle RF → Wi-Fi** – coût : 12-20 €.

------

## Liens directs (stock Europe)

| Produit                             | Lien                                                         | Prix repère |
| ----------------------------------- | ------------------------------------------------------------ | ----------- |
| **Adaptateur US → EU** (lot 2)      | Amazon – “Adaptateur US vers EU 2 broches” ([Amazon](https://www.amazon.fr/adaptateurs-voyage-adaptateur-Allemagne-appareils/dp/B0CKQWFKG5?utm_source=chatgpt.com)) | 8,99 €      |
| **Wiltec 30 Nm SW60**               | eBay – moteur SW60 30 Nm ([eBay](https://www.ebay.fr/itm/193466680780?utm_source=chatgpt.com)) | 32-70 €     |
| **Shelly 2PM** (module Wi-Fi volet) | Domadoo – Shelly 2PM Gen3 ([Domadoo](https://www.domadoo.fr/en/smart-lighting/7565-shelly-2pm-gen3-intelligent-wi-fi-dual-switch-micromodule-with-energy-measurement-3800235261903.html?srsltid=AfmBOopWzcBSAv9WlxhRJZtp2YOHGvSTkR40g3j9gTeU4FHjeEVRAtaa&utm_source=chatgpt.com)) | 31,99 €     |
| **Sonoff Dual R3**                  | Amazon – “Sonoff Dual R3 Wi-Fi” ([Amazon](https://www.amazon.fr/sonoff-dual-r3/s?k=sonoff+dual+r3&utm_source=chatgpt.com)) | 15-20 €     |

*(Les liens Amazon/eBay ouvrent directement la page produit.)*

------

## Packs conseillés

| Objectif                      | Matériel                                | Coût total |
| ----------------------------- | --------------------------------------- | ---------- |
| **Moins cher, 30 Nm + appli** | Wiltec 30 Nm + Shelly 2PM               | ≃ 65-70 €  |
| **Plug-and-play Tuya Wi-Fi**  | A-OK **AM45-20/17 MEL-W**               | ≃ 95-110 € |
| **Radio pro Somfy**           | Somfy Oximo RTS 30/17 + TaHoma (option) | ≃ 230 €    |

------

### ⚙️ Installer un pont RF → Wi-Fi (pour tes AM45/AM35 radio)

1. **Brancher** le pont Tuya RF433 ou Sonoff RF Bridge à 230 V (USB ou adaptateur).
2. **Appliquer** la procédure d’apprentissage : appuie sur « Prog » de la télécommande A-OK → le pont mémorise le code.
3. **Piloter** depuis Smart Life / eWeLink : ouvrir, fermer, scénarios (lever du soleil, présence, etc.).
4. (Facultatif) **Intégrer** dans Home Assistant via l’intégration officielle Tuya ou le plug-in eWeLink, sans cloud.

------

