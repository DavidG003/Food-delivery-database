# Cibora - Progettazione Database Food Delivery

## Descrizione del Progetto
Cibora è un sistema di food delivery progettato per gestire i dati di ristoranti aderenti, utenti, ordini e riders per la consegna. Il progetto si focalizza sulla creazione di un database relazionale efficiente, garantendo integrità e ottimizzazione delle operazioni.

## Funzionalità Principali
- **Gestione Utenti**: Registrazione, gestione ordini e borsellino elettronico.
- **Ristoranti**: Catalogazione per categorie, valutazioni, gestione menu e offerte.
- **Ordini**: Creazione, modifica, annullamento, gestione delle recensioni e codice sconto.
- **Riders**: Monitoraggio posizione in tempo reale, gestione mezzi di trasporto e statistiche sulle consegne.
- **Classifiche Mensili**: Riders più veloci, cibi più popolari, ristoranti più apprezzati, utenti top spender.

## Struttura del Database
Il database è stato progettato seguendo uno schema relazionale ottimizzato per efficienza e integrità dei dati.
- **Tabelle principali**: Utenti, Ristoranti, Ordini, Riders, Piatti, Recensioni.
- **Vincoli di integrità**: Foreign key per garantire la coerenza dei dati.
- **Ottimizzazioni**: Indici per migliorare le prestazioni delle query più frequenti.

## Tecnologie Utilizzate
- **Database**: PostgreSQL/MySQL
- **Modellazione**: Schema E-R e schema relazionale

## Struttura delle Tabelle
Il database include diverse entità principali, tra cui:
- **Utenti**: Informazioni personali, borsellino elettronico, cronologia ordini.
- **Ristoranti**: Dati generali, menu, recensioni, stato di Top Partner.
- **Ordini**: Dettagli degli ordini, stato, storicizzazione.
- **Riders**: Assegnazione degli ordini, gestione mezzi di trasporto.
- **Recensioni**: Valutazioni degli utenti su ristoranti e riders.
