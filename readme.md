# Database
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.


#Nome tabella: Macchine

#Colonne tabella: 
- id | BIGINT | AI, UNIQUE, NOT NULL
- casa_produttrice | VARCHAR(20) | NOT NULL
- modello | VARCHAR(20) | NULL
- prezzo | DECIMAL(8,2) NOT NULL
- cilindrata | MEDIUM | NULL
- targa | VARCHAR(8) | NOT NULL            
- cavalli | SMALL | NULL
- chilometraggio | MEDIUM | NULL 
- anno | YEAR | NULL
- alimentazione | VARCHAR(20) | NULL
- porte | TINYINT | NULL
- cambio | VARCHAR(20) | NOT NULL
- colore | VARCHAR(20) | NOT NULL
- posti | TINYINT | NULL
- foto | VARCHAR(255) | NULL