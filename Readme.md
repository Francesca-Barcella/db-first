# db-first
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario


Table name:
cars

Table Columns:
- id                            | BIGINT            | PK AI NOTNULL UNIQUE
- image                         | VARCHAR(255)      | NULL
- price                         | SMALLINT          | NOTULL
<!-- price meglio coi decimale perchè magari l'azienda vorrà fare dei calcoli -->
- price                         | DECIMAL (8,2)     |
- brand                         | VARCHAR(20)       | NOTULL
- model                         | VARCHAR(50)       | NOTULL
- color                         | VARCHAR(25)       | NULL
- year                          | YEAR              | NOTULL
- kms                           | MEDIUMINT         | NOTULL
- owners-number                 | TINYINT           | NULL
- transmission                  | VARCHAR(20)       | NULL
- fuel-type                     | VARCHAR(20)       | NULL
- category                      | VARCHAR(20)       | NULL
<!-- a volte scritto con entrambi i valori - esempio - 80 kW (109 CV) -->
- power-kw-cv                   | VARCHAR(20)       | NULL
<!-- displacement = cilindrata -->
- displacement                  | VARCHAR(10)       | NULL
- port-numbers                  | TINYINT           | NULL
- seat-numbers                  | TINYINT           | NULL
- certifications-and-warranties | VARCHAR(255)      | NULL
- description                   | TEXT              | NULL
- incidenti                     | TINYINT           | NULL
- vote                          | FLOAT (2,1)       | NULL
<!-- potrebbe essere utile per decidere se fissare apputamenti o meno, magari non è ancora arrivata in concessionaria -->
- is_available                  | TINYINT           | default(0)