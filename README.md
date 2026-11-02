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

## Estructura (30-35 minuts)

| Bloc | Pantalles | Temps |
|---|---|---|
| **Abans de res** | 2 preguntes anònimes | 3 min |
| **Què va passar** | Reel «Què és Blocus» i les dades (més de 130 detinguts, 89 menors, només 2 dels primers 128 amb antecedents) | 4 min |
| **La història del Pol** | 5 escenes amb pantalla partida (el Pol / qui ho organitza) i 3 votacions; acaba amb «Qui ha donat la cara?» | 10 min |
| **Els cartells** | Els cartells reals (carrusel de Newtral): qui els ha fet? i com reconèixer un cartell fet amb IA | 3 min |
| **Qui hi guanya?** | Reel «Qui hi ha darrere?», quatre hipòtesis amb «se sap / no se sap» i els culpables fàcils | 6 min |
| **Desmunta el missatge** | 4 missatges inventats: pressa, «som molts», premi, anonimat | 4 min |
| **Per acabar** | «Què li diries al Pol?», la frase final i què fer si et passa | 3 min |

## Reels

| Pantalla | Reel de Newtral |
|---|---|
| Què va passar | Què és Blocus i què passa amb les protestes |
| Els cartells | Noves convocatòries del 31 d'octubre (carrusel amb els cartells reals) |
| Qui hi ha darrere? | Qui hi ha darrere de Blocus Barcelona? |

A les pantalles de reels pots **afegir-ne** un altre enganxant l'enllaç (Instagram, TikTok o YouTube). Es guarda en aquell navegador. Per fixar-los per a tothom, posa'ls a `contingut.json`.

## Criteris de contingut

- **Res real que es pugui reutilitzar:** ni noms de canals, ni QR que funcionin, ni instruccions. Els cartells reals només es veuen a través de la notícia de Newtral, i els missatges són inventats.
- **Hipòtesis, no afirmacions:** la de l'ultradreta es presenta com el que és, la primera hipòtesi apuntada i sense cap vincle públic demostrat, al costat de les altres. Sobre els immigrants no hi ha cap informació que ho relacioni amb Blocus. Per això es tracta com a mecanisme general («culpar un col·lectiu sense proves»).
- **No ridiculitzar** els nois i noies que hi van anar: el focus és qui els va utilitzar.

Totes les dades i el contingut són a `contingut.json`. La sala és anònima i no desa res (Supabase Realtime, només missatges en directe).
