Descrizione

ESA Print Expert Collector è un'applicazione desktop sviluppata in Python per raccogliere e strutturare la conoscenza degli esperti di stampa 3D.

L'obiettivo del progetto è costruire un dataset reale utilizzabile per addestrare futuri modelli di Machine Learning e Deep Learning dedicati a:

Analisi della stampabilità
Previsione del successo di stampa
Raccomandazione parametri
Identificazione delle cause di fallimento
Automazione della preventivazione
Problema

Nel settore della stampa 3D gran parte delle decisioni vengono prese dall'esperienza dell'operatore.

Ad esempio:

Orientamento corretto del pezzo
Necessità di supporti
Materiale più adatto
Parametri macchina
Valutazione del rischio

Queste informazioni spesso non vengono archiviate in modo strutturato.

ESA Print Expert Collector nasce per trasformare l'esperienza dell'operatore in dati utilizzabili da sistemi AI.

Come funziona
1. Caricamento STL

L'utente seleziona un file STL.

Il software esegue automaticamente:

Calcolo volume
Calcolo superficie
Dimensioni X/Y/Z
Numero triangoli
Rapporto altezza/base
Controllo mesh chiusa
2. Screenshot

L'utente può allegare fino a 5 immagini:

Vista STL
Screenshot slicer
Supporti generati
Simulazioni
Foto della stampa reale

Le immagini vengono archiviate e collegate al record.

3. Valutazione esperto

L'operatore inserisce:

Materiale
Tecnologia
Orientamento
Supporti
Complessità
Livello di rischio
Stampabilità

4. Parametri di stampa

Possono essere registrati:

Temperatura ugello
Temperatura bed
Velocità
Layer
Infill
Ventola
Brim
Raft
5. Esito reale

Dopo la stampa vengono raccolti:

Successo o fallimento
Tempo reale
Costo reale
Motivo del fallimento
Note tecniche
