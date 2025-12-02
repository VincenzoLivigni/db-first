# DB Schema

- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## table name: VEHICLES (entity name: VEHICLE)

- id - BIGINT - PK - AI - NOT NULL
- title - VARCHAR(100) - NOT NULL
- type - VARCHAR(50) - NOT NULL
- brand - VARCHAR(30) - NOT NULL
- model - VARCHAR(50) - NOT NULL 
- license_plate - VARCHAR(10) - NULL - UNIQUE 
- description - TEXT - NULL 
- year - YEAR - NOT NULL
- kms - INT - NOT NULL
- price - DECIMAL(10,2) - NOT NULL
- seats - INT - NOT NULL
- doors - INT - NOT NULL
- transmission - VARCHAR(20) - NULL
- fuel_type - VARCHAR(30) - NULL
- availability - TINYINT - DEFAULT(0)
- color - VARCHAR(30) - NULL
- rating - FLOAT (2,1) - NULL
- image - VARCHAR(255) - NULL
- created_at - DATETIME - DEFAULT(now())
- update_at - DATETIME - DEFAULT(now())



