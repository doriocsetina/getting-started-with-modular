---
layout: default
title: "Introduzione"
permalink: /docs/3-moduli-e-utilizzo
---

# Moduli principali e loro utilizzo

Nel capitolo precedente abbiamo esplorato i concetti di base del Control Voltage (CV) e abbiamo iniziato a interagire con i moduli di un sintetizzatore modulare. In questo capitolo, costruiremo un sintetizzatore sottrattivo, uno dei tipi più comuni di sintetizzatori. Classicamente i sintetizzatori sottrattivi fanno parte della scuola 'East Coast' americana dei synth. In questo senso, i sintetizzatori east coast si basavano sul prendere un'onda già ricca di armoniche e modellare il suono togliendo, appunto, sottraendo informazioni armoniche per raggiungere il suono desiderato. 

Per fare ciò, aggiungeremo ulteriori oscillatori, descriveremo le diverse forme d'onda, introdurremo un filtro e spiegheremo il modulo MIDI-to-CV per controllare il sintetizzatore tramite una tastiera MIDI o direttamente la nostra tastiera!

## Oscillatori e Forme d'Onda

### Aggiungere un Secondo Oscillatore

Per creare suoni più ricchi e complessi, possiamo aggiungere un secondo oscillatore. Ogni oscillatore può generare diverse forme d'onda, ciascuna con caratteristiche sonore uniche. Le forme d'onda principali sono:

- **Onda Seno (Sine Wave)**: Un'onda pura senza armoniche, suona morbida e pulita.
- **Onda Triangolare (Triangle Wave)**: Ha solo armoniche dispari, suona più brillante di un'onda seno.
- **Onda Quadra (Square Wave)**: Ha armoniche dispari con ampiezza decrescente, suona ricca e piena.
- **Onda a Dente di Sega (Sawtooth Wave)**: Ha tutte le armoniche, suona molto brillante e tagliente.

Aggiungiamo un secondo oscillatore al nostro rack e colleghiamo le sue uscite allo scope per visualizzare le diverse forme d'onda.

### Collegare i Due Oscillatori

Colleghiamo le uscite dei due oscillatori a un mixer per combinare i loro segnali. Possiamo sperimentare con diverse forme d'onda e frequenze per creare suoni complessi. Tuttavia le frequenze degli oscillatori dovrebbero rimanere le stesse. Avere gli oscillatori a frequenze troppo diverse e soprattutto non a distanze frazionali farà suonare i due oscillatori molto male insieme. Teniamo le frequenze uguali. Se invece si vuole sperimentare con questa cosa, proviamo a renderli molto leggermente a distanza, avremo un effetto chorus-like, molto tipico dei vecchi sintetizzatori!

Dopo aver collegato i due oscillatori al mixer colleghiamo anche l'envelope all'ingresso CV dei VCA del mixer. Adesso premendo il push dell'envelope potremo sentire il suono dei due oscillatori messi assieme

![due oscillatori](/images/dueoscillatori.png)

## Filtro

### Introduzione al Filtro

Un filtro è un modulo che permette di modificare il contenuto armonico di un segnale audio. I filtri più comuni sono:

- **Filtro Passa-Basso (Low-Pass Filter, LPF)**: Attenua le frequenze sopra una certa soglia, lasciando passare solo le frequenze basse.
- **Filtro Passa-Alto (High-Pass Filter, HPF)**: Attenua le frequenze sotto una certa soglia, lasciando passare solo le frequenze alte.
- **Filtro Passa-Banda (Band-Pass Filter, BPF)**: Lascia passare solo una banda di frequenze, attenuando sia le frequenze basse che quelle alte.

Il filtro è un modulo importantissimo ed estremamente versatile per modellare e modificare il suono, ed è classicamente utilizzato nei sintetizzatori di tutti i tipi e molti hanno anche un suono molto caratteristico ed interi generi ci si sono sviluppati attorno, basti pensare all'acid! 

### Aggiungere un Filtro al Rack

Aggiungiamo un filtro passa-basso al nostro rack. Colleghiamo l'uscita del mixer all'ingresso del filtro e l'uscita del filtro all'uscita audio, mettendo il filtro come ultimo step della catena. Possiamo ora utilizzare il CV per controllare il cutoff del filtro, creando effetti di modulazione interessanti.

![filtro](/images/filtro.png)

## Modulo MIDI-to-CV

### Cos'è il Volt per Ottava (V/Oct)

Il Volt per Ottava (V/Oct) è uno standard di controllo per sintetizzatori modulari che permette di controllare la frequenza degli oscillatori tramite una tensione di controllo. Poiché ogni informazione è passata tramite voltaggio, questo standard è stato creato per poter inviare informazioni Ogni incremento di 1 volt corrisponde a un'ottava musicale.

### Aggiungere il Modulo MIDI-to-CV

Aggiungiamo un modulo MIDI-to-CV al nostro rack. Questo modulo converte i segnali MIDI da una tastiera o DAW in segnali CV che possono essere utilizzati per controllare gli oscillatori. Colleghiamo l'uscita V/Oct del modulo MIDI-to-CV all'ingresso V/Oct dei nostri oscillatori.

### Configurare il Modulo MIDI-to-CV

Configuriamo il modulo MIDI-to-CV per riconoscere la nostra tastiera MIDI. Una volta configurato, possiamo suonare le note sulla tastiera e vedere come gli oscillatori rispondono ai segnali CV, cambiando la loro frequenza in base alle note suonate.

## Conclusione

Ora che abbiamo aggiunto un secondo oscillatore, un filtro e un modulo MIDI-to-CV, abbiamo costruito un sintetizzatore sottrattivo completo. Possiamo sperimentare con diverse combinazioni di forme d'onda, impostazioni del filtro e modulazioni CV per creare una vasta gamma di suoni. Nel prossimo capitolo, esploreremo ulteriori moduli e tecniche per espandere ancora di più le capacità del nostro sintetizzatore modulare.