# db-first
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario


Table name:
cars

Table Columns:
- id | BIGINT
- image | VARCHAR(255)
- price | SMALLINT
- brand | VARCHAR(20)
- brand | VARCHAR(50)
- model | VARCHAR(50)
- color | VARCHAR(25)
- year | YEAR
- kms | MEDIUMINT
- owners-number | BIGINT
- transmission | VARCHAR(20)
- fuel-type | VARCHAR(20)
- category | VARCHAR(20)
<!-- a volte scritto con entrambi i valori - esempio - 80 kW (109 CV) -->
- power-kw-cv | VARCHAR(20)
<!-- displacement = cilindrata -->
- displacement | VARCHAR(10)
- port-numbers | BIGINT
- seat-numbers | BIGINT
- certifications-and-warranties | VARCHAR(255)
- description | VARCHAR(255)
- incidenti | BIGINT
- vote | BIGINT