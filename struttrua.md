<!-- sono presenti diversi Dipartimenti (es.: Lettere e Filosofia, Matematica, Ingegneria ecc.);
ogni Dipartimento offre più Corsi di Laurea (es.: Civiltà e Letterature Classiche, Informatica, Ingegneria Elettronica ecc..)
ogni Corso di Laurea prevede diversi Corsi (es.: Letteratura Latina, Sistemi Operativi 1, Analisi Matematica 2 ecc.);
ogni Corso può essere tenuto da diversi Insegnanti;
ogni Corso prevede più appelli d'Esame;
ogni Studente è iscritto ad un solo Corso di Laurea;
ogni Studente può iscriversi a più appelli di Esame;
per ogni appello d'Esame a cui lo Studente ha partecipato, è necessario memorizzare il voto ottenuto, anche se non sufficiente. -->




# Dipartimenti:
- id
- nome
- settore
- direttore
- email

# Corsi_laurea:
- id
- id_corso
- nome
- semestre
- durata_anni
- crediti
- descrizione

# Insegnanti
- id
- nome
- cognome
- email
- n_telefono
- id_dipartimento

# Studenti
- id
- nome
- cognome
- data-nascita
- data-iscrizione
- email
- n_telefono
- id_corso

# Esami
- id
- nome
- cfu
- n_appello

# Sessioni_esami
- id
- id_esame
- orario
- n_appello
- indirizzo

# voti_esami
- id_esame
- id_studente
- voto





