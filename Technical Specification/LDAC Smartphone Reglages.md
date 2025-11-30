```
Si tu veux, je peux te guider étape par étape pour vérifier sur ton S10e s’il est bien configuré en LDAC (avec captures d’écran ou instructions précises) ? 
oui
```

Parfait — allons-y, étape par étape, avec ton Samsung Galaxy S10e, pour vérifier que le codec LDAC est bien activé (et si besoin, l’activer). On va être pragmatique, clair, sans passer par quatre chemins.

------

### ✅ Pré‑requis

Avant tout :

- Ton écouteur ou casque Bluetooth **doit lui aussi supporter LDAC** (sinon le téléphone ne pourra pas l’utiliser). ([Samsung Community](https://r1.community.samsung.com/t5/galaxy-s/how-to-turn-on-aptx-and-ldac-on-exynos-s10/td-p/7548517?utm_source=chatgpt.com))
- Le casque doit être **connecté** au téléphone pendant que tu fais les réglages. ([Samsung Community](https://eu.community.samsung.com/t5/galaxy-s24-series/ldac-not-working/td-p/9063101/page/2?utm_source=chatgpt.com))
- Sois prêt à activer les “Options développeur” sur ton téléphone, car certains réglages sont là‑dedans. ([nextpit](https://www.nextpit.com/how-tos/how-to-check-change-bluetooth-codec-android-smartphones?utm_source=chatgpt.com))

------

### 🛠️ Étapes pour vérifier / activer LDAC

#### Étape 1 : Activer les Options développeur

1. Va dans **Paramètres** → **À propos du téléphone** (ou **À propos de l’appareil**).
2. Trouve la ligne “Numéro de version” ou “Build number” et tape dessus **7 fois**.
    → Voilà, Options développeur activées.

------

#### Étape 2 : Connecter ton casque/écouteurs compatibles LDAC

1. Depuis **Paramètres** → **Connexions** → **Bluetooth**, assure‑toi que le casque est bien appairé et connecté.
2. Une fois connecté, touche l’icône « roue dentée » à côté de son nom pour accéder aux **Paramètres de l’appareil Bluetooth**.

------

#### Étape 3 : Activer LDAC dans les réglages de l’appareil Bluetooth

1. Dans la page des détails du casque connecté (la roue dentée), cherche une option du type **Codec audio Bluetooth**, ou **Qualité audio HD**, ou directement “LDAC”.
2. Active l’interrupteur “LDAC” s’il est présent.
    → Exemple d’un utilisateur : « To turn on LDAC … go to the BT menu … gear icon … enable LDAC. » ([Reddit](https://www.reddit.com/r/galaxys10/comments/166slhv/ldac_on_s10/?utm_source=chatgpt.com))
3. Si l’option est grisée ou absente, c’est probablement que le casque **ne supporte pas LDAC**, ou que la version matérielle du téléphone/logiciel ne l’autorise pas. ([Samsung Community](https://eu.community.samsung.com/t5/overige-galaxy-s-series/ldac-not-suported-on-galaxy-s10/td-p/1102307?utm_source=chatgpt.com))

------

#### Étape 4 : (Optionnel mais recommandé) Régler le débit LDAC

1. Depuis **Paramètres** → **Options développeur** → descends jusqu’à la section **Bluetooth audio codec / Bluetooth audio LDAC playback quality**. ([Guide des Casques Pro](https://headphoneguidepro.com/ldac-codec-enable-hi-res-audio-on-android/?utm_source=chatgpt.com))
2. Là, tu devrais voir des choix comme :
   - Optimized for audio quality (990 kbps)
   - Balanced audio & connection quality (660 kbps)
   - Optimized for connection quality (330 kbps)
3. Choisis “Optimized for audio quality (990 kbps)” si ta connexion Bluetooth est stable et proche. Sinon, choisis le compromis 660 kbps.
    → Exemple : « You must tap Optimized for Audio Quality (990kbps/909kbps) to use Hi‑Res audio. » ([Guide des Casques Pro](https://headphoneguidepro.com/ldac-codec-enable-hi-res-audio-on-android/?utm_source=chatgpt.com))

------

### 🔍 Vérification finale

- Joue un morceau audio depuis ton téléphone.
- Retourne dans les détails du casque (Bluetooth → appareil → roue dentée) : vérifie que “LDAC” est bien affiché comme codec actif.
- Si tu veux, tu peux utiliser une appli d’analyse ou vérifier dans l’appli du casque (certains modèles Sony, etc.) que le codec utilisé est bien LDAC.
- Si malgré tout tu vois “AAC” ou autre codec plus bas que LDAC : cela signifie que l’un des maillons ne supporte pas LDAC (le casque ou le téléphone/firmware).

------

### ⚠️ À prendre en compte

- Même si le téléphone et le casque supportent LDAC, **la qualité dépend encore du fichier audio/streaming** : un MP3 128 kbps ne sortira pas miraculeusement comme du FLAC 24‑bit. ([nextpit](https://www.nextpit.com/how-tos/how-to-check-change-bluetooth-codec-android-smartphones?utm_source=chatgpt.com))
- Si tu es loin du téléphone ou beaucoup d’obstacles (murs, interférences), le système peut rétrograder automatiquement à un débit plus faible (660 ou 330 kbps) pour maintenir la connexion.
- L’activation du débit maximal (990 kbps) peut entraîner une **consommation batterie plus élevée** (dans le téléphone et le casque).

------

Si tu veux, je peux te donner **des captures d’écran précises pour la version One UI** de ton S10e (et même un mini‑vidéo), afin que ce soit **visuel** et ultra‑clair. Veux‑tu qu’on le fasse ?