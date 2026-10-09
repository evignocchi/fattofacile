---
name: fattofacile
description: Il tuo sito. Senza complicazioni. Crema, verde bosco, un solo corallo per la spunta e l'azione, Inter 800 stretta.
colors:
  verde: "#0F5F51"
  verde-scuro: "#0A4A3E"
  menta: "#DCEBE3"
  menta-2: "#C9E0D5"
  corallo: "#EE745D"
  corallo-testo: "#B93E25"
  pesca: "#FFE3DA"
  crema: "#F5F6EE"
  carta: "#FAFCF4"
  inchiostro: "#252623"
  grafite: "#585956"
  linea: "#DADDD0"
typography:
  display:
    fontFamily: "Inter, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(40px, 6.2vw, 78px)"
    fontWeight: 800
    lineHeight: 1.04
    letterSpacing: "-0.04em"
  headline:
    fontFamily: "Inter, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(32px, 4.4vw, 56px)"
    fontWeight: 800
    lineHeight: 1.04
    letterSpacing: "-0.04em"
  title:
    fontFamily: "Inter, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(20px, 2vw, 24px)"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-0.02em"
  body:
    fontFamily: "Inter, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Inter, Segoe UI, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 600
    lineHeight: 1.35
rounded:
  sm: "12px"
  md: "16px"
  lg: "22px"
  xl: "28px"
  pill: "999px"
spacing:
  gutter: "clamp(18px, 4vw, 48px)"
  section: "clamp(72px, 9vw, 128px)"
  stack: "clamp(72px, 9vw, 130px)"
  control: "56px"
components:
  button-primary:
    backgroundColor: "{colors.corallo}"
    textColor: "{colors.inchiostro}"
    rounded: "{rounded.pill}"
    padding: "0 30px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "#F2836D"
  button-solid:
    backgroundColor: "{colors.verde}"
    textColor: "{colors.carta}"
    rounded: "{rounded.pill}"
    padding: "0 30px"
    height: "56px"
  button-solid-hover:
    backgroundColor: "{colors.verde-scuro}"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.verde}"
    rounded: "{rounded.pill}"
    padding: "0 30px"
    height: "56px"
  button-small:
    backgroundColor: "{colors.corallo}"
    textColor: "{colors.inchiostro}"
    rounded: "{rounded.pill}"
    padding: "0 20px"
    height: "44px"
  window:
    backgroundColor: "{colors.carta}"
    rounded: "{rounded.lg}"
  window-bar:
    backgroundColor: "{colors.crema}"
    padding: "12px 16px"
  pill:
    backgroundColor: "{colors.carta}"
    textColor: "{colors.inchiostro}"
    rounded: "{rounded.pill}"
    padding: "0 16px 0 12px"
    height: "40px"
  window-tag:
    backgroundColor: "{colors.menta}"
    textColor: "{colors.grafite}"
    rounded: "{rounded.pill}"
    padding: "5px 10px"
  input:
    backgroundColor: "{colors.carta}"
    textColor: "{colors.inchiostro}"
    rounded: "{rounded.md}"
    padding: "0 18px"
    height: "56px"
  form-card:
    backgroundColor: "{colors.carta}"
    rounded: "{rounded.xl}"
    padding: "clamp(22px, 3vw, 36px)"
---

# Design System: fattofacile

## Overview

**Creative North Star: "Il sito che si costruisce davanti a te"**

Crema come terra, verde bosco per i campi di colore e le sezioni di peso, corallo solo per la spunta e per l'azione. Il sistema vive di una sola figura, la finestra del browser in carta con bordo sottile e ombra morbida, che nell'hero si costruisce da sola e poi ritorna in piccolo in ogni sezione (ricerca, portale, rinnovo, preventivo). La pagina dimostra la promessa invece di descriverla.

Il tono visivo e' caldo e diretto: titoli in Inter 800 molto stretta, evidenziatore menta sulle parole chiave, pillole a 999px per ogni elemento cliccabile o di stato, nessun colore o carattere oltre a quelli del marchio. La densita' e' ariosa, sezioni da 72 a 128px, un solo reveal per sezione, nessun parallasse.

Il marchio e' vincolante: logo wordmark verde bosco con spunta corallo (SVG fornito, varianti positivo, negativo, bianco, mono), icona "f" bianca su quadrato arrotondato verde, sfondo crema.

**Key Characteristics:**
- Tre colori portanti (crema, verde, corallo) piu' inchiostro per il testo; menta e pesca come supporti.
- Un solo font, Inter, con il peso 800 riservato ai titoli.
- La finestra browser e' l'unico oggetto grafico; niente icone decorative, niente fotografie stock.
- Pillole 999px per bottoni, tag, chip, nav; raggi grandi (16-28px) per contenitori.
- Movimento solo in ingresso e a dimostrazione, tutto spento con prefers-reduced-motion.

## Colors

Palette a terra crema con un campo verde profondo e un unico accento caldo; la proporzione dichiarata nel brand e' crema 60, verde 30, corallo 7, inchiostro 3.

### Primary
- **Verde Bosco** (verde): titoli h1-h3, campi di colore (sezione prezzo scura), bottone pieno, focus ring, selezione, accenti di stato attivo.
- **Corallo** (corallo): il bottone CTA principale "Voglio il mio sito" e la spunta del marchio. Su fondo chiaro e come testo la spunta e le scritte usano la variante Corallo Testo.

### Secondary
- **Verde Profondo** (verde-scuro): hover del verde, evidenziatore su fondo scuro, testo del messaggio di conferma.
- **Corallo Testo** (corallo-testo): corallo scurito per spunte piccole, timbro "Online", errori, testo su pesca; garantisce contrasto dove il corallo pieno non basta.

### Tertiary
- **Menta** (menta) e **Menta Scura** (menta-2): evidenziatore sulle parole chiave, tag della finestra, risposta della chat, sezione contatto, testo secondario su verde, scheletri.
- **Pesca** (pesca): fondo dei messaggi di errore del modulo.

### Neutral
- **Crema** (crema): terra della pagina, barra della finestra, nav.
- **Carta** (carta): superficie della finestra, campi, schede, sezione "leve"; anche testo su verde.
- **Inchiostro** (inchiostro): testo corrente e testo sui bottoni corallo.
- **Grafite** (grafite): testo secondario, sottotitoli.
- **Linea** (linea): bordi sottili 1px, divisori, tratteggi.

### Named Rules
**The Coral Is Action Rule.** Il corallo compare solo sulla spunta e sull'azione (CTA, timbro, interruttore barrato). Mai come riempimento decorativo o su titoli.

**The Mint Marker Rule.** Le parole chiave dei titoli si evidenziano con una banda menta al 52% dell'altezza del corpo, che si disegna all'ingresso; su fondo verde la banda diventa verde profondo.

## Typography

**Display Font:** Inter 800 (con Segoe UI, system-ui, sans-serif), file locali in assets/fonts (400, 500, 600, 700, 800)
**Body Font:** Inter 400/500 (stesso stack)
**Label/Mono Font:** nessuno distinto; i numeri usano tabular-nums.

**Character:** una sola famiglia, contrasto di peso e di spaziatura negativa. I titoli sono stretti e pesanti, il corpo e' neutro e leggibile.

### Hierarchy
- **Display** (800, clamp(40px, 6.2vw, 78px), 1.04, -0.04em): solo h1 dell'hero.
- **Headline** (800, clamp(32px, 4.4vw, 56px), 1.04, -0.04em): h2 di sezione; nelle leve scende a clamp(30px, 3.6vw, 46px).
- **Title** (700, clamp(20px, 2vw, 24px), 1.2, -0.02em): h3, passi di "come funziona".
- **Body** (400, 17px, 1.6): testo corrente, max 60ch, text-wrap pretty. Sottotitolo a clamp(18px, 1.6vw, 21px) in grafite.
- **Label** (600-700, 14-15px): pillole, nav (500), etichette dei campi, nomi dei siti.
- **Numeri grandi** (800, fino a clamp(80px, 13vw, 176px), tabular-nums, -0.04em): il prezzo; il totale del preventivo e il rinnovo seguono la stessa regola a scala minore.

### Named Rules
**The One Family Rule.** Solo Inter. Il peso 800 e' per titoli e cifre grandi, il 700 per bottoni e sottotitoli, 400-500 per il corpo.

**The Tight Headline Rule.** Ogni titolo ha tracking negativo (-0.02em a -0.04em) e text-wrap balance.

## Layout

Contenitore centrato a 1160px con gutter fluido clamp(18px, 4vw, 48px). Sezioni con padding verticale clamp(72px, 9vw, 128px); le leve sono righe a due colonne (1fr / 1.05fr) con ordine alternato e distanza fra righe clamp(72px, 9vw, 130px). L'hero e' uno split 1.02fr / .98fr con testo a sinistra e finestra dimostrativa a destra. La galleria dei siti e' una griglia di tre colonne (due sotto 900px, una sotto 560px); "come funziona" e' una linea del tempo orizzontale a tre passi che diventa verticale sotto 760px. Le colonne collassano a una sotto 900px. Sotto 700px compare una barra CTA fissa in basso. La nav e' sticky, 72px, con voci nascoste sotto 860px. Target tattili minimi 44px (controlli principali 56px).

## Elevation & Depth

Ibrido: piatto per default, strati tonali (crema, carta, menta) e un solo vocabolario d'ombra morbida per gli oggetti che galleggiano.

### Shadow Vocabulary
- **Finestra** (`box-shadow: 0 1px 2px rgba(37,38,35,.06), 0 18px 40px -18px rgba(15,95,81,.28)`): finestre, form, timbro e chip dell'hero.
- **CTA corallo** (`box-shadow: 0 14px 28px -14px rgba(238,116,93,.9)`): solo sul bottone corallo grande.
- **Barra mobile** (`box-shadow: 0 18px 36px -12px rgba(37,38,35,.5)`): bottone nella barra fissa.
- **Focus campo** (`box-shadow: 0 0 0 4px rgba(15,95,81,.16)`): anello morbido sul campo attivo.

### Named Rules
**The Soft Shadow Rule.** Le ombre sono diffuse, con tinta verde o inchiostro e offset verticale ampio. Nessuna ombra netta o spostata.

## Shapes

Pillole a 999px per bottoni, nav, tag, chip, pillole, interruttori e barre URL. Contenitori morbidi: finestra 22px (18px nella galleria), form 28px, campi 16px, schede interne 12-16px, riquadri foto 16px, indicatori tondi 50%. Bordi sottili da 1px in Linea sulle superfici; bordo 2px su campi e bottoni outline; tratteggio 1px dashed per righe del preventivo e del rinnovo. Le tre pallini della barra finestra sono tondi da 10px in Linea.

## Components

### Buttons
- **Shape:** pillola completa (999px), altezza 56px, padding 0 30px, Inter 700 17px.
- **Primary (corallo):** fondo corallo, testo inchiostro, ombra corallo; hover schiarisce a un corallo piu' chiaro e solleva di 2px; la freccia si sposta di 3px.
- **Solid (verde):** fondo verde, testo carta, hover verde profondo.
- **Outline:** bordo 2px verde, testo verde; hover riempie di verde.
- **Small:** 44px, padding 0 20px, 15px, nella nav.
- **Focus:** contorno 3px verde con offset 3px (carta sulle sezioni scure). Disabled: opacita' .6.

### Window (signature)
Superficie carta, bordo 1px Linea, raggio 22px, ombra Finestra. Barra superiore crema con tre pallini, barra URL a pillola o tag di titolo. Contiene l'hero che si costruisce, il preventivo, il confronto, la ricerca, il portale, il rinnovo e gli screenshot dei siti reali.

### Pills and Tags
- **Pillola di garanzia:** carta, bordo Linea, 40px, spunta corallo scuro a sinistra, 14px 600.
- **Tag della finestra:** menta, grafite, 11px, 700, maiuscolo con tracking .06em, solo dentro la barra finestra come titolo dell'oggetto.
- **Timbro "Online" e chip:** timbro carta con bordo 2px corallo scuro ruotato -6deg; chip verde e corallo con ombra Finestra.

### Inputs / Fields
- **Style:** carta, bordo 2px Linea, raggio 16px, altezza 56px, Inter 500 17px, dentro una scheda form carta da 28px.
- **Focus:** bordo verde piu' anello morbido 4px.
- **Error:** bordo e messaggio in Corallo Testo, messaggio su pesca; conferma su menta con testo verde profondo.

### Navigation
Sticky su crema al 90% con sfocatura; voci a pillola da 44px, 15px 500 grafite, hover menta con testo verde; bordo inferiore Linea compare allo scroll. Logo a sinistra, CTA piccola a destra.

### Switch and Disclosure
Interruttore di rinnovo 46x28px, verde acceso e grigio spento, cursore carta; al disattivo il prezzo viene barrato con linea corallo da 3px. Le domande frequenti sono details con indicatore tondo menta da 32px (piu' che diventa meno, verde se aperto).

### Timeline
Linea Linea da 3px che si riempie di corallo all'ingresso, nodi tondi carta con bordo 3px verde.

## Do's and Don'ts

### Do:
- **Do** usare il corallo solo per la CTA, la spunta e il timbro; il testo corallo e' sempre Corallo Testo.
- **Do** tenere i titoli in Inter 800 con tracking negativo e un'unica parola chiave evidenziata in menta.
- **Do** mostrare le promesse dentro una finestra browser carta (22px, bordo 1px, ombra Finestra) invece che con icone o schede uguali.
- **Do** dare a ogni elemento interattivo una pillola da almeno 44px e il contorno di focus verde da 3px.
- **Do** usare un solo reveal per sezione e rispettare prefers-reduced-motion spegnendo ogni animazione.
- **Do** usare il logo SVG fornito, rispettando lo spazio di rispetto e le versioni del brand.

### Don't:
- **Don't** introdurre colori o caratteri nuovi.
- **Don't** usare ombre nette o spostate; solo l'ombra morbida tinta.
- **Don't** usare il corallo come campo di colore decorativo o come testo piccolo su crema.
- **Don't** aggiungere parallasse o animazioni continue fuori dalla dimostrazione dell'hero.
- **Don't** costruire righe di card tutte uguali al posto della finestra dimostrativa.
