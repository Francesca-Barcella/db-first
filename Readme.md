# db-first
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario


Table name:
cars

Table Columns:
- id | BIGINT | PK AI NOTNULL UNIQUE
- image | VARCHAR(255) | NULL
- price | SMALLINT | NOTULL
- brand | VARCHAR(20) | NOTULL
- model | VARCHAR(50) | NOTULL
- color | VARCHAR(25) | NULL
- year | YEAR | NOTULL
- kms | MEDIUMINT | NOTULL
- owners-number | BIGINT  | NULL
- transmission | VARCHAR(20) | NULL
- fuel-type | VARCHAR(20) | NULL
- category | VARCHAR(20) | NULL
<!-- a volte scritto con entrambi i valori - esempio - 80 kW (109 CV) -->
- power-kw-cv | VARCHAR(20) | NULL
<!-- displacement = cilindrata -->
- displacement | VARCHAR(10) | NULL
- port-numbers | BIGINT | NULL
- seat-numbers | BIGINT | NULL
- certifications-and-warranties | VARCHAR(255) | NULL
- description | TEXT | NULL
- incidenti | BIGINT | NULL
- vote | BIGINT | NULL