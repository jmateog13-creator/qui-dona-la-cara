# ✊ Qui dona la cara?

Activitat de tutoria sobre **Blocus** (octubre de 2026): perfils de TikTok i canals de Telegram que van reclutar joves per a disturbis i saquejos. L'objectiu no és renyar, sinó entendre el mecanisme: **qui hi posa la cara i qui hi guanya**.

## Obrir

- **Profe (pantalla gran):** `index.html`
- **Alumnes:** `movil.html`, o escanejant el QR, amb el codi de 4 números. Anònim, sense registrar-se.
- **Previsualitzar sense sala:** `index.html?demo` (simula 24 alumnes)

**Espai** o **→** avança (i revela els vots), **←** torna enrere.

### Enllaç fix per al Moodle

Si obres la pantalla del profe amb un codi fix, la sala sempre té el mateix codi, i l'enllaç dels alumnes no canvia mai:

- **Profe:** `index.html?codi=1234`
- **Alumnes (al Moodle):** `movil.html?c=1234`. Entren directament, sense escriure res.

Tria un número que no facin servir altres profes alhora.

## Estructura (uns 50 minuts)

1. **Abans de res:** tres preguntes anònimes, sense respostes bones ni dolentes.
2. **Què va passar:** reels incrustats i les dades (més de 130 detinguts, 89 menors i només 2 dels primers 128 amb antecedents).
3. **La història del Pol:** història inventada amb fets reals, amb la pantalla partida. A l'esquerra, el que viu el Pol; a la dreta, el que fa en aquell moment qui ho organitza. La classe vota què faria a cada moment, i després surt què va fer el Pol. Acaba amb la comparativa «Qui ha donat la cara?».
4. **Els cartells:** un cartell d'exemple inventat (amb QR desactivat), «qui l'ha fet?» i com reconèixer un cartell fet amb IA.
5. **Qui hi guanya?:** quatre hipòtesis amb «què se sap / què no se sap» (efecte mirall, oportunisme, ultradreta i injerència estrangera), i una alerta sobre els culpables fàcils.
6. **Desmunta el missatge:** sis missatges inventats i sis trucs (pressa, enemic comú, «som molts», premi, anonimat i «passa-ho»). Són els mateixos que a les estafes i al control en parella.
7. **Per acabar:** què li diries al Pol el primer dia, i què fer si et passa.
8. **Fonts.**

## Reels

A la pantalla «Què va passar», enganxa l'enllaç d'un reel d'**Instagram**, **TikTok** o **YouTube** i prem **Afegir reel**. Es queda guardat en aquell navegador.

Per fixar-los per a tothom, posa'ls a `contingut.json`, a la llista `"reels"`:

```json
"reels": ["https://www.instagram.com/reel/XXXX/", "https://www.tiktok.com/@newtral/video/123"]
```

## Criteris de contingut

- **Res real que es pugui reutilitzar:** ni noms de canals, ni QR que funcionin, ni instruccions. El cartell i els missatges són inventats.
- **Hipòtesis, no afirmacions:** la de l'ultradreta es presenta com el que és, la primera hipòtesi apuntada i sense cap vincle públic demostrat, al costat de les altres. Sobre els immigrants no hi ha cap informació que ho relacioni amb Blocus. Per això es tracta com a mecanisme general («culpar un col·lectiu sense proves»).
- **No ridiculitzar** els nois i noies que hi van anar: el focus és qui els va utilitzar.

Totes les dades i el contingut són a `contingut.json`. La sala és anònima i no desa res (Supabase Realtime, només missatges en directe).
