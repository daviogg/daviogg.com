---
title: Blocchi vuoti
date: 2021-04-29 09:00:00
tags:
    - Bitcoin
category: tech
keywords:
    - Stratum
    - Blockchain
---


# Perché la Blockchain di bitcoin contiene dei blocchi vuoti?

## **Come funziona il mining di Bitcoin?**

La grandezza massima di un blocco è di 1MB.

La difficulty della Proof of work è calibrata in modo che un blocco venga minato ogni 10 minuti circa.

Il miner è poi incentivato a recuperare quante più transazioni possibile e con le fee più alte, in modo da ricevere un compenso maggiore una volta minato il blocco scelto.
Quindi, in definitiva, il compenso deriva dalla somma delle fee di tutte le transazioni più il reward garantito una volta trovato il “[nonce](https://en.bitcoinwiki.org/wiki/Nonce)” del blocco.

Fatte queste considerazione è particolare notare che nella blockchain ci sono all’incirca il **19% dei blocchi vuoti** (contengono solamente la transazione coinbase per recapitare il compenso al miner).

## Perché ci sono dei blocchi vuoti?

Cominciamo con il fare una precisazione: un blocco vuoto non è più facile o economico da minare, quindi a cosa è dovuto?

Una parte dei blocchi è vuota a causa del basso utilizzo della rete nei primi anni in cui BTC è stato messo in funzione. Non essendoci sufficienti transazioni nella [mempool](https://github.com/bitcoin-core/bitcoin-devwiki/wiki/Mempool-and-mining), il miner operava comunque e completava i blocchi vuoti così da poter garantire sicurezza e stabilità al network. I miner erano anche incentivati da un reward per blocco molto più consistente di oggi.

A partire invece dal 2016, il premio è diminiuto a 12.5btc per ogni blocco minato, inoltre le fee cominciarono ad aumentare. Non c’è quindi nessun motivo apparente per il quale i miner dovessero decidere di escludere le transazioni dal blocco.

Così negli ultimi anni il numero di blocchi vuoti è sceso allo 0.04% ma è comunque un numero abbastanza elevato, giusto?

Il problema è dovuto ad una limitazione tecnica nota.

[continua...](https://daviogg.medium.com/perch%C3%A9-la-blockchain-di-bitcoin-contiene-dei-blocchi-vuoti-4e35aa2dec26)