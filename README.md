# Algoritmi Genetici - Stack Problem

Questo progetto implementa un Algoritmo Genetico (AG) per risolvere lo Stack Problem, ideato da John Koza nel 1992. L'obiettivo è comporre la parola "UNIVERSAL" impilando correttamente blocchi etichettati con lettere, inizialmente disposti in modo casuale su un tavolo.

Il progetto è sviluppato in Mathematica, sfruttando le sue capacità di calcolo simbolico e la gestione di strutture dati ad albero per rappresentare gli individui dell’algoritmo.

## Contenuti

- Introduzione agli Algoritmi Genetici
- Definizione dello Stack Problem
- Implementazione dell’algoritmo:
  - Individui
  - Popolazione
  - Valutazione (fitness)
  - Selezione, crossover, mutazione
- Analisi dei risultati
- Prospettive di sviluppo

## Struttura dell’Algoritmo

L’algoritmo segue un approccio evolutivo:

1. Creazione di una popolazione iniziale di individui casuali
2. Calcolo della fitness per ogni individuo
3. Selezione dei genitori tramite roulette di probabilità
4. Crossover per generare figli
5. Introduzione di nuovi individui (mutazione)
6. Ripetizione del processo per un numero definito di generazioni

## Funzioni Utilizzate

Ogni individuo è rappresentato come un albero decisionale, costruito utilizzando:

### Funzioni algebriche
- `TB` (top block)
- `MS` (move to stack)
- `MT` (move to table)
- `NN` (next needed)
- `CS` (current stack)

### Funzioni logiche
- `EQ` (equal)
- `DU` (do until)
- `NOT` (negazione logica)

Le funzioni sono utilizzate in combinazioni sintatticamente corrette per costruire programmi validi.

## Risultati

L’algoritmo è stato testato su 1000 configurazioni iniziali. Nella maggior parte dei casi la convergenza alla soluzione avviene in meno di 20 generazioni. Le soluzioni trovate sono inoltre testate su configurazioni alternative per valutarne la generalizzazione.

## Prospettive Future

- Migliorare la generalità delle soluzioni trovate
- Minimizzare il numero di mosse necessarie
- Validare le soluzioni su molteplici casi iniziali
- Introdurre ulteriori operatori genetici o strategie evolutive

## Requisiti

- Wolfram Mathematica

## Come eseguire

Aprire il file contenente l’algoritmo in Mathematica e avviare l’esecuzione seguendo i commenti presenti nel codice.

