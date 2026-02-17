# NeuroFriction v5

Aplicació d'entrenament neuronal amb àudio binaural, reptes cognitius i exploració de coneixement.

---

## ⚠️ IMPORTANT: UTILITZA LA VERSIÓ 5!

> 🎯 **DESCARREGA I USA:** `neurofriction-5.html` ← **AQUESTA ÉS LA VERSIÓ CORRECTA!**
> 
> ❌ **NO UTILITZIS:** `neurofriction-3.html` (versió antiga, sense funcions noves)
>
> La versió 5 inclou TOTES les funcionalitats:
> - ✅ Mode NeuroExplora amb 96 píndoles de coneixement
> - ✅ Sistema de repetició espaiada
> - ✅ Export/Import de dades
> - ✅ Editor de píndoles personalitzades
> - ✅ Feedback hàptic
> - ✅ Dashboard de progrés
> - ✅ Repte diari i molt més!

---

## 🚀 Com Utilitzar l'App

### Opció 1: Ús Local (Més Fàcil)

1. **Descarrega l'arxiu**: Baixa `neurofriction-5.html` al teu dispositiu
2. **Obre l'arxiu**: Fes doble clic a `neurofriction-5.html` o obre'l amb el teu navegador (Chrome, Firefox, Safari, Edge)
3. **Comença a usar-lo**: L'aplicació funcionarà immediatament sense necessitat d'instal·lar res

> ⚠️ **Important**: Per l'àudio binaural, necessites **auriculars** i donar permís al navegador per reproduir àudio.

### Opció 2: Instal·lar com a PWA (Aplicació)

#### En Mòbil (Android/iOS):

1. Obre `neurofriction-5.html` amb Chrome (Android) o Safari (iOS)
2. Toca el menú del navegador (⋮ o )
3. Selecciona **"Afegeix a la pantalla d'inici"** o **"Add to Home Screen"**
4. L'aplicació apareixerà com una app nativa al teu telèfon

#### En Ordinador (Chrome/Edge):

1. Obre `neurofriction-5.html` amb Chrome o Edge
2. Cerca la icona d'instal·lació a la barra d'adreces (⊕)
3. Fes clic a **"Instal·la NeuroFriction"**
4. L'aplicació s'instal·larà com una app independent

### Opció 3: Desplegar a un Servidor Web

Si vols compartir l'app o accedir-hi des de múltiples dispositius:

1. **GitHub Pages** (Gratuït):
   ```bash
   # Crea un repositori a GitHub
   # Activa GitHub Pages a Settings → Pages
   # Puja neurofriction-5.html, manifest.json i sw.js
   # Accedeix a: https://usuari.github.io/repo/neurofriction-5.html
   ```

2. **Netlify/Vercel** (Gratuït):
   - Puja els arxius a Netlify Drop o Vercel
   - Obtindràs una URL pública automàticament

3. **Servidor Propi**:
   ```bash
   # Copia els arxius al teu servidor web
   cp neurofriction-5.html manifest.json sw.js /var/www/html/
   ```

## 📱 Arxius Necessaris

- `neurofriction-5.html` - Aplicació principal (Progressive Web App) - **OBLIGATORI**
- `manifest.json` - Manifest PWA - Opcional (millora PWA)
- `sw.js` - Service Worker - Opcional (funcionament offline)

### Icones PWA (Opcionals)

Per una millor experiència PWA, pots crear:
- `icon-192.png` - Icona 192x192px
- `icon-512.png` - Icona 512x512px

Pots crear aquestes icones amb [PWA Builder](https://www.pwabuilder.com/) o [RealFaviconGenerator](https://realfavicongenerator.net/).

## 🆚 Comparació de Versions

| Característica | v3 (antiga) | v5 (nova) ✨ |
|----------------|-------------|--------------|
| Modes bàsics | ✅ 6 modes | ✅ 7 modes |
| NeuroExplora | ❌ | ✅ 96 píndoles |
| Repetició espaiada | ❌ | ✅ |
| Export/Import dades | ❌ | ✅ |
| Editor píndoles | ❌ | ✅ |
| Feedback hàptic | ❌ | ✅ |
| Dashboard progrés | ❌ | ✅ |
| Repte diari | ❌ | ✅ |
| PWA complet | ⚠️ Bàsic | ✅ Complet |

**→ Utilitza sempre `neurofriction-5.html` per accedir a totes les funcionalitats!**

## Modes Disponibles

1. **Sessió Viva** - Mutacions microfrequències
2. **No-Control** - Sense pausa ni temps visible
3. **Antibiais Brutal** - Destrucció d'opinions
4. **Insight Asimètric** - Gamma curt + theta llarg
5. **Claredat Mental** - Progressió alfa→beta→gamma
6. **Ment Superior** - Theta-gamma coupling + reptes
7. **NeuroExplora** - Exploració de coneixement amb 96 píndoles

## Funcionalitats

- 🎵 Àudio binaural amb ones theta, alfa, beta i gamma
- 🧠 Theta-Gamma Coupling per memòria de treball
- 💡 96 píndoles de coneixement (12 categories × 8 items)
- 📊 Repetició espaiada amb intervals [1, 3, 7, 21, 60 dies]
- 📥 Export/Import de dades en JSON
- ✏️ Editor visual de píndoles personalitzades
- 📈 Dashboard de progrés amb gràfics
- 📳 Feedback hàptic (iOS i Android)
- 🌐 PWA amb funcionament offline
- 🎯 Repte diari determinístic
- 🔊 Ambientació sonora per categoria

## Tecnologia

- HTML5 + CSS3 + JavaScript vanilla
- Web Audio API
- LocalStorage per persistència
- Service Workers per funcionament offline
- Web Share API
- Vibration API

## ⚡ Guia Ràpida

1. **Obre** `neurofriction-5.html` al navegador
2. **Connecta auriculars** (essencial per l'àudio binaural)
3. **Selecciona un mode** (comença amb "Sessió Viva" o "NeuroExplora")
4. **Ajusta** la durada i intensitat
5. **Fes clic a "Iniciar"** i concedeix permís d'àudio
6. **Tanca els ulls** i deixa't guiar per l'àudio

## 🔧 Solució de Problemes

### No s'escolta l'àudio
- ✅ Comprova que tens auriculars connectats
- ✅ Augmenta el volum del sistema i de l'app
- ✅ Dona permís al navegador per reproduir àudio
- ✅ Intenta fer clic al botó "Iniciar" de nou

### L'aplicació no es carrega
- ✅ Utilitza un navegador modern (Chrome, Firefox, Safari, Edge)
- ✅ Comprova que JavaScript està habilitat
- ✅ Prova obrir l'arxiu en mode incògnit/privat

### No funciona en mòbil
- ✅ Assegura't d'usar Safari (iOS) o Chrome (Android)
- ✅ Obre l'arxiu des d'un servidor web o GitHub Pages
- ✅ Dona permisos d'àudio quan se sol·licitin

### Les dades no es guarden
- ✅ No utilitzis mode incògnit/privat
- ✅ Comprova que el navegador permet LocalStorage
- ✅ Usa les funcions Export/Import per fer còpies de seguretat

## 📞 Suport

Si tens problemes o preguntes:
- Revisa la [documentació tècnica](README.md)
- Comprova que tens la versió 5 (`neurofriction-5.html`)
- Prova amb un altre navegador

## ❓ Per què hi ha dues versions?

**neurofriction-3.html** (antiga)
- Versió original amb funcionalitats bàsiques
- Es manté per compatibilitat amb usuaris que ja l'utilitzen
- ⚠️ No té les funcionalitats noves

**neurofriction-5.html** (ACTUAL) ✨
- Versió completa amb totes les funcionalitats
- Inclou 10 funcions noves
- ✅ **És la que has d'utilitzar!**

> 💡 Si ja utilitzaves la v3, pots exportar les teves dades i importar-les a la v5.

## Llicència

Copyright © 2026 NeuroFriction
