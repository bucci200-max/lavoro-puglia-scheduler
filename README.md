# Lavoro Puglia — scheduler

Questo repository contiene **solo** il workflow GitHub Actions che avvia, ogni 12 minuti di giorno
e ogni 30 di notte (ora di Roma),
la pipeline di raccolta e pubblicazione delle offerte di lavoro di
[Lavoro Puglia](https://t.me/lavoropuglia26).

Il codice della pipeline è in un repository privato e viene letto con una deploy key in sola lettura.
Credenziali e stringhe di connessione sono conservate come *GitHub Actions secrets* e non compaiono
nei log.
