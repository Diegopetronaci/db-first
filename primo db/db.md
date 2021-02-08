
# database name: GameStop
# nome tabelle: Videogiochi

- id number BIGINT PRIMARYKEY NOTNULL AUTO_INCREMENT
- titolo string VARCHAR(30) NOTNULL
- pegi number TINYINT NOTNULL
- casa_produttrice string VARCHAR(10) NOTNULL
- copertina string text NULL
- max_n_giocatori_locali number TINYINT NULL
- max_n_giocatori_online number TINYINT NULL
- GB_minimi number SMALL NOTNULL
- licenza string number TINYINT NOTNULL
- lingua string VARCHAR(15) NOTNULL
- console string VARCHAR(20) NOTNULL
- descrizione string TEXT NULL
- dlc_incorporati number TINYINT NULL
- disponibilità number TINYINT NULL DEFAULT(0)
- n_disponibilità number MEDIUMINT NULL DEFAULT(0)
- data_uscita DATE NOTNULL
- isbn number TINYINT UNIQUE
- prezzo number FLOAT(6,2)