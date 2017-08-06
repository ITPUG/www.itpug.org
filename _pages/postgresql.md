---
permalink: /postgresql/
title: "PostgreSQL: il DBMS Open Source più avanzato al mondo!"
excerpt: "ITalian PostgreSQL Users Group"
layouts_gallery:
  - url: /assets/images/mm-layout-splash.png
    image_path: /assets/images/mm-layout-splash.png
    alt: "splash layout example"
  - url: /assets/images/mm-layout-single-meta.png
    image_path: /assets/images/mm-layout-single-meta.png
    alt: "single layout with comments and related posts"
  - url: /assets/images/mm-layout-archive.png
    image_path: /assets/images/mm-layout-archive.png
    alt: "archive layout example"
last_modified_at: 2017-08-05T14:28:13-05:00
---

{% include gallery id="layouts_gallery" caption="Facilmente riconoscibili: `PostgreSQL`, `ITPUG`, `Community`" %}

PostgreSQL è un potente database-relazionale open source.

Vanta più di 15 anni di sviluppo attivo e un'architettura collaudata che gli ha fatto guadagnare una consolidata reputazione di affidabilità, integrità dei dati oltre che a livello di correttezza.

Funziona su tutti i principali sistemi operativi, tra cui Linux, UNIX (AIX, BSD, HP-UX, SGI IRIX, MacOS, Solaris, Tru64) e Windows.

ACID completamente compatibile, ha un pieno supporto per le chiavi esterne, unisce, visualizza, attiva e memorizza le procedure (in più lingue). Include la maggior parte dei tipi di dati SQL: 2008, inclusi INTEGER, NUMERIC, BOOLEAN, CHAR, VARCHAR, DATE, INTERVAL e TIMESTAMP.

Supporta anche la memorizzazione di oggetti grandi binari, tra cui immagini, suoni o video. Ha interfacce di programmazione native per C / C ++, Java, .Net, Perl, Python, Ruby, Tcl, ODBC, e, tra le altre cose, la sua documentazione è eccezionale.

Database di classe enterprise, PostgreSQL vanta funzioni sofisticate come MultiVision Concurrency Control (MVCC), ripristino in tempo reale, spazi di tabelle, replica asincrona, transazioni nidificate (punti di salvataggio), backup online / hot, un sofisticato pianificatore di query / ottimizzatore di query e scrivere Avanzare la registrazione per la tolleranza agli errori.

Supporta i set di caratteri internazionali, codifiche di carattere multibyte, Unicode e è locale-aware per l'ordinamento, la sensibilità dei casi e la formattazione.

È estremamente scalabile sia nella quantità pura di dati, che nella gestione del numero di utenti concorrenti che può ospitare.

PostgreSQL è un progetto dinamico grazie alla sua Community molto attiva che ogni anno rilascia una nuova major release di questo fantastico progetto.

## Licenza BSD

*Copyright (c) -year-, -copyright holder- All rights reserved.*

* **Redistribution and use in source and binary forms, with or without modification, are permitted** *provided that the following conditions are met:*

* **Redistributions of source code** *must retain the above copyright notice, this list of conditions and the following disclaimer.*

* **Redistributions in binary** *form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.*

* *Neither the name of the -organization- nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.*

## Puntiamo il riflettore sulle varie release di PostgreSQL

PostgreSQL nasce a metà degli anni 80 come progetto di ricerca presso l'Università di California (Berkeley).
Inizia a prendere vigore a partire dal 1995.

Grazie al contributo di centinaia di sviluppatori provenienti da tutto il mondo, è un progetto molto stabile e lo sviluppo attuale prosegue in modo consistente al ritmo di una major release l’anno.

Oggi PostgreSQL è uno dei progetti Open Source di maggior successo.

* 2017: **PostgreSQL 10**
* 2016: **PostgreSQL 9.6** Parallel Queries, Multi sync standby servers, Smarter Foreign Data Wrappers, Phrase search
* 2016: **PostgreSQL 9.5** “Upsert” (INSERT ... ON CONFLICT), BRIN (Block Range Indexes), pg_rewind, Import Foreign Schema, Inheritance with foreign tables
* 2014: **PostgreSQL 9.4** Logical replication, Replication slots, JSONB
* 2013: **PostgreSQL 9.3** Writable Foreign Data Wrappers, Materialised Views, JSON functions and operators, LATERAL
* 2012: **PostgreSQL 9.2** Cascading Replication, Index-Only scans, pg_stat_statements, JSON, Ranges
* 2011: **PostgreSQL 9.1** Synchronous Replication, Writable CTEs, Extensions, Foreign Data, Wrappers, Unlogged tables, Serialisable Snapshot Isolation, Column collations
* 2010: **PostgreSQL 9.0** HOT Standby, Streaming Replication, Column Triggers, Conditional Triggers, hstore
* 2009: **PostgreSQL 8.4** Window functions, CTEs, Database collations, Per-Column permissions
* 2008: **PostgreSQL 8.3** HOT updates, Asynchronous commit. XML, Fulltext search, Distribuited checkpoints
* 2007: **PostgreSQL 8.2** Warm Standby, SQL 2003, Concurrent Index Builds, GIN index
* 2005: **PostgreSQL 8.1** Table partitioning, Bitmap scans, Two-Phase commits, autovacuum
* 2005: **PostgreSQL 8.0** PITR, Tablespace, Windows support, Savepoints
* 2000: Dal 2000 al 2005 vengono rilasciate 5 nuove release: **PostgreSQL 7**
* 1997: Dal 1997 al 2000 vengono rilasciate 6 nuove release: **PostgreSQL 6**
* 1995: 1° maggio 1995: il progetto **Postgre95 V0.01** parte e successivamente diventa -> **PostgreSQL 1.0**
* 1994 – 1995: **Postgres95** (Jolly Chen e Andrew Yu)
* 1986 – 1993: **University Postgres** [Michael Stonebraker](----)

## Per i più curiosi: le fasi dello sviluppo di PostgreSQL

Tutto nasce dal bisogno di nuove funzionalità che possono emergere per scopi diversi: Commerciali, Accademici, Interesse personale (in pieno spirito hacker). Senza trascurare la presenza occasionale di committenti.

Le nuove funzionalità vengono **proposte** in **due finestre temporali**, chiamate **Commit fest**.

Le proposte hanno la forma di vere e proprie **patch complete di documentazione**.

* **Review:** ad ogni patch viene assegnato un esperto che dovrà valutare se applicare la patch al codice
* **Beta:** viene rilasciata una versione per testing diffuso
* Fase di pre-rilascio: la comunità prepara gli annunci nelle principali lingue (italiano incluso)
* Viene rilasciata la versione M.m.0
* Inizia il periodo di manutenzione che può durare diversi anni
* La comunità PostgreSQL supporta le ultime 5 macro release

[Vai al sito ufficiale di PostgreSQL]({{ "https://www.postgresql.org/"}}){: .btn .btn--success .btn--large}
