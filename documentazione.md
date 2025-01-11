---
layout: default
title: "Documentazione della progettazione dell'e-learning"
permalink: /documentazione
---

# Documentazione della progettazione dell'e-learning

# Indice

- [Documentazione della progettazione dell'e-learning](#documentazione-della-progettazione-delle-learning)
- [Indice](#indice)
- [1. Analisi per la definizione della macrotipologia didattica](#1-analisi-per-la-definizione-della-macrotipologia-didattica)
  - [1.1 Analisi dell'utenza](#11-analisi-dellutenza)
  - [1.2 Analisi degli obiettivi](#12-analisi-degli-obiettivi)
    - [Conoscenza:](#conoscenza)
    - [Comprensione:](#comprensione)
    - [Applicazione:](#applicazione)
    - [Sintesi:](#sintesi)
  - [1.3 Analisi del contenuto formativo](#13-analisi-del-contenuto-formativo)
  - [1.4 Analisi dell'infrastruttura](#14-analisi-dellinfrastruttura)
- [2. Definizione della macro-tipologia didattica](#2-definizione-della-macro-tipologia-didattica)
  - [2.1 Modalità di e-learning](#21-modalità-di-e-learning)
  - [2.2 Blending](#22-blending)
  - [2.3 Autogeneratività](#23-autogeneratività)
- [3. Definizione metodologico-didattica](#3-definizione-metodologico-didattica)
  - [3.1 Scelte metodologiche](#31-scelte-metodologiche)
    - [3.1.1 Metodologia didattica](#311-metodologia-didattica)
    - [3.1.2 Strategia di comunicazione](#312-strategia-di-comunicazione)
    - [3.1.3 Valutazione](#313-valutazione)
  - [3.2 Documento operativo](#32-documento-operativo)
    - [3.2.1 Struttura del corso](#321-struttura-del-corso)
    - [3.2.2 Storyboard](#322-storyboard)
    - [3.2.3 Layout e navigazione](#323-layout-e-navigazione)
- [4. Contenuto e dialogo](#4-contenuto-e-dialogo)

# 1. Analisi per la definizione della macrotipologia didattica

## 1.1 Analisi dell'utenza

L’utenza a cui è riferita la lezione è chiunque si voglia avvicinare al mondo della sintesi modulare. Non sono presupposte conoscenze specializzate tuttavia familiarità anche vaga con termini chiave nell’ambito musicale facilitano la comprensione del corso. Per l’esecuzione degli esempi proposti è presupposto l’accesso a un sintetizzatore (preferibilmente modulare o semimodulare) o una macchina in grado di eseguire il software free-and-open-source VCV rack per simulare un sintetizzatore modulare.

## 1.2 Analisi degli obiettivi

L’obiettivo di questa lezione è fornire le basi e spiegare i concetti chiave per poter utilizzare un sintetizzatore modulare e comprenderne i suoi componenti e concetti più basilari, tramite i quali l’utente può approfondire autonomamente il funzionamento delle componenti non esplicitamente menzionate e soprattutto esplorare i suoni creabili attraverso synth modulari. 

### Conoscenza: 

- Significato di termini chiave, tra cui
  - Frequenza
  - Pitch
  - Control Voltage
  - Modulazione
  - Patch

- Ruolo dei diversi moduli basilari, tra cui
  - Oscillatore
  - LFO (Low Frequency Oscillator)
  - Filtri 
  - VCA (Voltage Controlled Amplifier)
  - Envelope

### Comprensione: 

  - Funzionamento del Control Voltage (CV)
  - Uso del routing
  - Funzionamento dei singoli moduli

### Applicazione:

  - Generare suoni tramite gli oscillatori
  - Modificare caratteristiche dei suoni tramite filtri e VCA
  - Controllare e modellare le modalità di modifica tramite inviluppi (envelopes) ed LFO

### Sintesi:

  - Creare autonomamente patch e nuovi suoni al di fuori degli esempi dati

## 1.3 Analisi del contenuto formativo

| LEZIONE | CHIUSO/APERTO | STABILE/INSTABILE | TESTUALITÀ, MULTIMEDIALITÀ, INTERATTIVITÀ |
|---------|---------------|-------------------|-------------------------------------------|
| 1. Introduzione alla sintesi e ai sintetizzatori modulari | **CHIUSO**<br>si tratta di nozioni specifiche e spiegazioni tecniche | **STABILE**<br>sono nozioni tecniche stabilite che non sono soggette a cambiamenti | **TESTUALE**, **MULTIMEDIALE**<br>saranno presenti testi, immagini e video per facilitare la comprensione dei concetti |
| 2. Control Voltage, segnali e manipolazione dei parametri del suono | **CHIUSO/APERTO**<br>si tratteranno nozioni tecniche tuttavia operando esemplificazioni | **STABILE**<br>sono nozioni tecniche stabilite che non sono soggette a cambiamenti | **TESTUALE**, **MULTIMEDIALE**, **INTERATTIVA**<br>saranno presenti testi, immagini e video per facilitare la comprensione dei concetti.<br>Nel caso l’utente faccia uso della guida e degli esempi guidati tramite un sintetizzatore o il software consigliato l’utente potrà interagire direttamente con i concetti consigliati. |
| 3. Moduli di un sintetizzatore sottrattivo e utilizzo | **CHIUSO/APERTO**<br>si tratteranno nozioni tecniche tuttavia operando esemplificazioni. L’utilizzo delle varie componenti del sintetizzatore possono cambiare in base alla volontà dell’utente | **INSTABILE**<br>i moduli presentati, spiegati e utilizzati sono soggetti a costanti cambiamenti | **TESTUALE**, **MULTIMEDIALE**, **INTERATTIVA**<br>saranno presenti testi, immagini e video per facilitare la comprensione dei concetti.<br>Nel caso l’utente faccia uso della guida e degli esempi guidati tramite un sintetizzatore o il software consigliato l’utente potrà interagire direttamente con i concetti consigliati. |


## 1.4 Analisi dell'infrastruttura

Il corso, i cui file risiedono in una repository pubblica su Github, utilizza Github Pages come sua infrastruttura, il quale deploya una pagina web statica tramite Jekyll. La pagina web è quindi in grado di renderizzare i file markdown dove risiedono l'interezza dei contenuti del corso: i contenuti sono principalmente testuali tuttavia ampliati tramite immagini, GIF e link esterni. 

L'utilizzo di questa piattaforma ha un duplice scopo: il primo è la semplicità di accesso, l'utente necessita solamente di una macchina con un browser e una connessione ad internet per accedere ai contenuti del corso. Da qui può seguire le lezioni proposte parallelamente al software di simulazione VCV rack o seguirle parallelamente all'utilizzo di una sintetizzatore hardware. L'utente tramite il browser può quindi accedere alle molteplici risorse esterne e, all'interno di github pages, sfruttare le risorse multimediali i collegamenti ipertestuali per muoversi fra le risorse caricate. 

Allo stesso tempo, l'utilizzo di github pages consente un deployment continuo delle lezioni tramite Github actions. In questo modo, se il docente o la comunità volessero aggiungere una nuova lezione alla repository pubblica, questa sarà immediatamente accessibile al pubblico tramite la pagina di Github Pages, consentendo una condivisione immediata ed efficiente. Inoltre l'utilizzo dei file markdown come medium della scrittura del corso rende il learning object estremamente portabile: il plain text può essere renderizzato ovunque come può essere esportato in maniera rich in pdf e quindi scaricato e ricondiviso. La licenza CC0 della repository a questo proposito ne spinge la condivisione e la libera distribuzione.  

# 2. Definizione della macro-tipologia didattica

## 2.1 Modalità di e-learning

Il corso può considerarsi web-based training tuttavia potrebbe presentare alcuni elementi di support online learning, poiché le dinamiche di interazione possono essere soggette a cambiamento in base allo spread della repository. 

Di default la repository è una risorsa online liberamente accessibile la quale tuttavia non presuppone in nessun modo una relazione tutor-studente, per cui l'interazione tra il creatore della repository ed i suoi fruitori è distante, e lo studente interagisce e studia individualmente i contenuti della repository. Inoltre la repository presenta collegamenti esterni, di conseguenza l'apprendimento ha un forte focus sull'esplorazione individuale, guidata dalla repository però tuttavia ultimamente in mano all'utente.

## 2.2 Blending

Il corso non presuppone nessun tipo di incontro dal vivo. L'implementazione di questo corso dal vivo implicherebbe l'individuazione di docenti ed altre risorse fuori dallo scope del progetto. Tuttavia, nell'ipotesi di un incontro dal vivo, per la natura del corso sarebbe utile adibirle alla familiriazione tecnologica, cosicché l'installazione dei software possa avvenire in un contesto collettivo e inoltre all'esigenza di socializzare, la quale può essere una forte componente in vista di creare una comunità


## 2.3 Autogeneratività

Per la natura del corso e del medium della repository, se questo fosse lanciato all'interno di forum o di comunità di qualche tipo ci sarebbero le potenzialità di autogeneratività ed espansione del corso stesso. La repository è dotata di mezzi per creare issues e per includere altri membri della comunità nella scrittura di nuove lezioni, aggiornamento delle lezioni già presenti, o anche la risposta a eventuali issues proposti dall'utenza, instaurando quindi una dinamica di interazione basata sulla comunità, tuttavia non classicamente prevedibile. Però, per la natura del corso e il suo focus finale sulla sperimentazione è inevitabile pensare al processo di condivisione individuale come estremamente arricchente per coloro che abbiano interesse a perseguire ulteriormente la materia del corso.

Allo stesso tempo è utile ricordare come l'autogeneratività si basi a dinamiche esterne alla piattaforma del corso. L'esistenza di discorsi, forum e spazi è già presente al di fuori della repository in maniera abbondante, e se questa può essere un tool utile all'avvicinamento di alcune persone, la dinamica generativa avviene necessariamente in luoghi diversi da quelli della repository. 

# 3. Definizione metodologico-didattica

## 3.1 Scelte metodologiche

### 3.1.1 Metodologia didattica

Per semplicità è utilizzato un modello sequenziale poiché il corso, essendo mirato a un utenza inesperta, specialmente all'inizio mira a fornire una base teorica di nozioni che costruiscono ognuna sulla precedente. 

Tuttavia, al di fuori dell'introduzione, i collegamenti principali avvengono tramite ipertesto e la sequenzialità è uno strumento più utile alla facilità di consultazione che all'ordine di apprendimento. Dalla terza lezione in poi i riferimenti ipertestuali presenti all'interno delle lezioni ne consentono un utilizzo consultorio non necessariamente legato alla sequenzialità con cui viene proposta nella repository. 

### 3.1.2 Strategia di comunicazione

Le lezioni sono in larga parte testuali, tuttavia presentano numerose immagini esplicative, schemi e GIF, poiché quete comunicano in maniera più immediata gli esempi replicabili tramite il software o i sintetizzatori utilizzati. Inoltre numerosi dei concetti tecnici presentano una visualizzazione più facilmente intuibile tramite immagini e animazioni, le quali sono tutte embeddabili all'interno dei file markdown. Sono anche presenti riferimenti a contenuti interattivi esterni, su altre piattaforme che implementano un'interazione utile alla comprensione dei concetti spiegati all'interno delle slide. Tutti i contenuti multimediali e i collegamenti ipertestuali al di là delle semplici immagini saranno tuttavia ridondanti per poter conservare l'utilità del learning object anche se usufruito in formato pdf statico.   

### 3.1.3 Valutazione

Non è previsto nessun metodo di valutazione in questo corso: la natura del corso in sé rende piuttosto controintuitiva una valutazione in senso classico dell'apprendimento condiviso in questa repository. Lo studente è chiamato a riprodurre gli esempi proposti durante la lettura, di conseguenza si crea automaticamente una dinamica di autovalutazione, dove l'output di una procedura è descritto attentamente e lo studente può valutare il suo percorso in base all'eventuale riuscita nella riproduzione degli esempi guidati. Inolte, laddove non vi sono esempi guidati le lezioni mirano ad una proattività ed esplorazione sonora da parte dello studente, la quale non è possibile valutare quantitativamente. 

## 3.2 Documento operativo

### 3.2.1 Struttura del corso

### 3.2.2 Storyboard 

### 3.2.3 Layout e navigazione

Il corso è presentato in maniera lineare nel nav a sinistra della pagina, dove è possibile visionare tutte le lezioni presenti. È evidenziata la pagina su cui ci si trova ed in cima di ogni lezione vi è un indice della lezione, in maniera da poter immediatamente riconoscere gli argomenti trattati dalla stessa. L'indice di ogni lezione è ipertestuale e consente la navigazione rapida ai contenuti della lezione, per facilitarne la consultazione. 

Il titolo riporta alla home dove è presente la sinossi del corso. 

L'header laterale dove è presente il nav presenta anche i bottoni per il download delle lezioni.

# 4. Contenuto e dialogo

Questo corso immagina uno sviluppo inizialmente lineare: alla progettazione metodologico-didattica seguirà la realizzazione dei materiali che verranno poi erogati tramite pubblicazione online. Poichè tuttavia il corso tratta un argomento di dimensioni vastissime è possibile che il processo di progettazione, realizzazione e interazione siano ampliati attraverso community, nel caso questa si possa radunare attorno alla risorsa.