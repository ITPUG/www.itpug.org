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

![PostgreSQL]({{site.baseurl}}/assets/images/pgSQL.jpg)

{% include gallery caption="`PostgreSQL`, `Database Relazionale`, `Open Source`, `Licenza BSD`, `ITPUG`, `Community`" %}

[PostgreSQL](https://www.postgresql.org/){:target="_blank"} è un potente database-relazionale open source.

Vanta più di 15 anni di sviluppo attivo e un'architettura collaudata che gli ha fatto guadagnare una consolidata reputazione di affidabilità, integrità dei dati oltre che a livello di correttezza.

<iframe width="100%" height="400" src="https://time.graphics/embed?v=1&id=171601" frameborder="0" allowfullscreen></iframe>
<div><a  style="font-size: 12px; text-decoration: none;" title="Roadmap timeline" href="https://time.graphics">Roadmap timeline</a></div>

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

* **2020 (24 Settembre)**: **[PostgreSQL 13](https://www.postgresql.org/about/press/presskit13/){:target="_blank"}** Notable enhancements include *space savings and performance gains from de-duplication of B-tree index entries*, *Parallel vacuuming of indexes*, *improved performance for queries that use aggregates or partitioned tables* and *better usage of extended statistics when planning queries*.
* **2019 (3 ottobre)**: **[PostgreSQL 12](https://www.postgresql.org/about/press/presskit12/){:target="_blank"}** Notable improvements to query performance, particularly over larger data sets, and overall space utilization,  new capabilities such as SQL/JSON path expression support, optimizations for how common table expression (WITH) queries are executed, and generated columns. 
* **2018 (18 ottobre)**: **[PostgreSQL 11](https://www.postgresql.org/about/press/presskit11/it/){:target="_blank"}** Increased Robustness and Performance for Partitioning, Transactions Supported in Stored Procedures, Enhanced Capabilities for Query Parallelism, Just-in-Time (JIT) Compilation for Expressions
* **2017 (5 ottobre)**: **[PostgreSQL 10](https://www.postgresql.org/about/press/presskit10/it/){:target="_blank"}** Logical replication, declarative table partitioning, improved query parallelism
* **2016 (29 settembre)**: **[PostgreSQL 9.6](https://www.postgresql.org/about/press/presskit96/it/){:target="_blank"}** Parallel Queries, Multi sync standby servers, Smarter Foreign Data Wrappers, Phrase search
* **2016 (7 gennaio)**: **[PostgreSQL 9.5](https://www.postgresql.org/about/press/presskit95/it/){:target="_blank"}** “Upsert” (INSERT ... ON CONFLICT), BRIN (Block Range Indexes), pg_rewind, Import Foreign Schema, Inheritance with foreign tables
* **2014 (18 dicembre)**: **[PostgreSQL 9.4](https://www.postgresql.org/about/press/presskit94/it/){:target="_blank"}** Logical replication, Replication slots, JSONB
* **2013 (9 settembre)**: **[PostgreSQL 9.3](https://www.postgresql.org/about/press/presskit93/it/){:target="_blank"}** Writable Foreign Data Wrappers, Materialised Views, JSON functions and operators, LATERAL
* **2012 (10 settembre)**: **[PostgreSQL 9.2](https://www.postgresql.org/about/press/presskit92/it/){:target="_blank"}** Cascading Replication, Index-Only scans, pg_stat_statements, JSON, Ranges
* **2011 (12 settembre)**: **[PostgreSQL 9.1](https://www.postgresql.org/about/press/presskit91/it/){:target="_blank"}** Synchronous Replication, Writable CTEs, Extensions, Foreign Data, Wrappers, Unlogged tables, Serialisable Snapshot Isolation, Column collations
* **2010 (20 settembre)**: **[PostgreSQL 9.0](https://www.postgresql.org/about/press/presskit90/it/){:target="_blank"}** HOT Standby, Streaming Replication, Column Triggers, Conditional Triggers, hstore
* **2009 (1° luglio)**: **[PostgreSQL 8.4](https://www.postgresql.org/about/news/1108/){:target="_blank"}** Window functions, CTEs, Database collations, Per-Column permissions
* 2008 (4 febbraio): **[PostgreSQL 8.3](https://www.postgresql.org/about/news/918/){:target="_blank"}** HOT updates, Asynchronous commit. XML, Fulltext search, Distribuited checkpoints
* 2006 (5 dicembre): **PostgreSQL 8.2** Warm Standby, SQL 2003, Concurrent Index Builds, GIN index
* 2005 (8 novembre): **PostgreSQL 8.1** Table partitioning, Bitmap scans, Two-Phase commits, autovacuum
* 2005 (19 gennaio): **PostgreSQL 8.0** PITR, Tablespace, Windows support, Savepoints
* 2000: Dal 2000 al 2005 vengono rilasciate 5 nuove release: **PostgreSQL 7**
* 1997: Dal 1997 al 2000 vengono rilasciate 6 nuove release: **PostgreSQL 6**
* 1995: 1° maggio 1995: il progetto **Postgre95 V0.01** parte e successivamente diventa -> **PostgreSQL 1.0**
* **1994 – 1995**: **[Postgres95](https://www.postgresql.org/docs/8.4/static/history.html){:target="_blank"}** (Jolly Chen e Andrew Yu)
* 1986 – 1993: **[University of California at Berkeley](https://www.postgresql.org/docs/8.4/static/history.html){:target="_blank"}** ([Michael Stonebraker](https://en.wikipedia.org/wiki/Michael_Stonebraker){:target="_blank"})


![PostgreSQL](https://upload.wikimedia.org/wikipedia/en/timeline/6ee67b277be3b78e63fefb49e9fcf0a4.png)

_[Grafico Wikipedia](https://en.wikipedia.org/wiki/PostgreSQL)_

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
