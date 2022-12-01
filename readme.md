# Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

#Table name: cars

id: BIGINT | PK | AI NOTNULL UNIQUE
brand: VARCHAR(20)| NOT NULL
model: VARCHAR(15) | NOT NULL
chilometres: SMALL / MEDIUMINT | NULL
year: YEAR | NULL
fuel: VARCHAR(20) | NULL
price: DECIMAIL(8,2) | NULL
engine capacity: SMALL / MEDIUMINT | NULL
owners: TINYINT | NULL
doors: TINYINT | NULL
description: TEXT

