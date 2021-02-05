
# database name: Hotel
# nome tabelle: Stanze

- id_camera PRIMARYKEY AUTO_INCREMENT BIGINT NOTNULL
- n_camere_disponibile SMALL NOTNULL
- n_letti TINYINT NULL
- descrizione_personale TEXT NULL
- informazioni_clienti NOTNULL
- prezzo FLOAT(8,2) NOTNULL
- giorni_prenotazione TINYINT NOTNULL
- parcheggio TINYINT NULL
- stelle FLOAT(2,1) NOTNULL
- pensione TINYINT NULL
- n_personale BIGINT NULL
- n_clienti BIGINT NULL