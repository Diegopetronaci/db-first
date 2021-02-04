
# database name: GameStop
# nome tabelle: Videogiochi

- id number BIGINT PRIMARYKEY NOTNULL AUTO_INCREMENT UNIQUE
- titolo string VARCHAR(30) NOTNULL
- pegi number TINYTINT NOTNULL
- casa_produttrice string VARCHAR(10) NOTNULL
- copertina string text NULL
- max_n_giocatori_locali number TINYTINT NULL
- max_n_giocatori_online number TINYTINT NULL
- GB_minimi number SMALL NOTNULL
- licenza string number TINYTINT NOTNULL
- lingua string VARCHAR(15) NOTNULL
- console string VARCHAR(20) NOTNULL
- descrizione string TEXT NULL
- dlc_incorporati number TINYTINT NULL
- disponibilità number TINYTINT NULL DEFAULT(0)
- n_disponibilità number MEDIUMINT NULL DEFAULT(0)
- data_uscita DATE NOTNULL
- isbn number TINYINT UNIQUE
- prezzo number FLOAT(6,2)