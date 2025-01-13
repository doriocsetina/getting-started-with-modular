---
layout: default
title: "Introduzione"
permalink: /docs/1-intro
---

# Introduzione al suono e ai sintetizzatori modulari

## Introduzione

***You have the possibility with electronic music to generate any texture, in theory, and any sound, so why would any musician would limit themselves?***

SOPHIE parla di questo in una sua intervista ad arte TRACKS: la promessa dei sintetizzatori è proprio questo landscape potenzialmente infinito di suoni e possibilità ed i sintetizzatori modulari, dove ogni pezzo è individualmente selezionabile e patchabile in maniera personalizzata sembra lo strumento perfetto con cui raggiungere questo scopo. 

Se nei normali sintetizzatori i suoni e i segnali hanno un routing predefinito - gli oscillatori entrano nei filtri, il voltage-controlled-amplifier agisce sul volume, l'inviluppo gestisce il vca - invece i sintetizzatori modulari ti consentono di scegliere i moduli e le funzionalità e patcharle a proprio piacimento. 
Vuoi creare una drum machine generativa? Prendi una turing machine, un physical modeler e un sequencer e sei a poche patch di distanza da una batteria. Vuoi creare un sintetizzatore ambient-drone? raccogli oscillatori granulatori e delay per creare un muro del suono imponente. 

L'assemblaggio di un sintetizzatore modulare è quindi un processo estremamente personale, che ti consente di creare uno strumento su misura, e con immense possibilità di esplorazione. 

Tuttavia per comprendere il funzionamento dei sistemi modulari è importantissimo comprendere i segnali che ne attraversano i cavi patch: i suoni e il control voltage.

## Suono, frequenza e armoniche

Quando ascoltiamo un qualunque suono ciò che arriva materialmente alle nostre orecchie sono delle onde! Precisamente parliamo di onde sonore poiché il suono si trasmette tramite delle onde con dei picchi di alta pressione e delle valli di bassa pressione nell'aria. Le onde sonore e i suoni hanno delle caratteristiche fondamentali:

### Ampiezza

L'ampiezza delle onde sonore è a tutti gli effetti il volume. Un'onda più ampia trasmette più energia e la sentiamo ad un volume più alto. 

![amplitude scheme](/images/amplitude.gif)

### Frequenza

La frequenza (spesso chiamata pitch) di un suono determina quanto lo percepiamo grave o acuto. A livello tecnico è il numero di vibrazioni che l'onda sonora compie in una determinata unità di tempo. Più la frequenza è alta più picchi ci saranno nella stessa unità di tempo e più acuto risulterà il suono alle nostre orecchie. Ogni nota musicale è quindi una specifica frequenza.

![frequency scheme](/images/frequency.gif)

### Armoniche

Se le note musicali corrispondono a delle frequenze, qual è la differenza tra la stessa nota emessa da strumenti differenti? Intuitivamente ci viene semplice la differenza di un Fa di una chitarra e del Fa di un pianoforte: 'suonano' diversi. Cos'è quindi a cambiare? 

La chiave sono le armoniche: delle vere e proprie "componenti" del suono che in combinazione fra loro in diverse quantità creano suoni differenti

![harmonic scheme](/images/harmonics.png)

Ogni suono lo possiamo immaginare come una somma di tante onde "pure" ossia sinusoidali, tutte a frequenze diverse. La nota principale che percepiamo è detta la frequenza 'fondamentale', solitamente è anche la componente a più alta ampiezza. Tutte le altre note che compongono il suono e l'onda sonora sono le armoniche, che formano il timbro del suono. Tutte queste armoniche comunemente sono analizzate tramite lo spettro armonico. Lo spettro armonico mostra sull'asse delle X le frequenze del suono analizzate e sull'asse delle Y l'ampiezza di queste frequenze. Ogni frequenza è quindi un'armonica, e si potrà vedere come la fondamentale sarà il picco dello spettro armonico. Operare dei cambiamenti allo spettro armonico è comunemente riferito come 'equalizzare' un suono, ossia modificare e modellare l'ampiezza delle frequenze per modificarne il timbro e la qualità.

Ora che abbiamo qualche informazione basilare sul suono possiamo passare al prossimo step, l'altro segnale che attraversa i cavi patch di ogni modulare: il control voltage. A questa breve introduzione segue una guida pratica su come installare VCV Rack, e successivamente la guida per spiegare il Control Voltage farà uso di esempi pratici che potrai replicare sul tuo sintetizzatore o su VCV. 