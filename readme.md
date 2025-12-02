<!-- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario -->

# Tabella: used_cars

id          | INT PRIMARY KEY AUTO_INCREMENT  NOT NULL
brand       | VARCHAR(20)                     NOT NULL
model       | VARCHAR(50)                     NOT NULL
year        | YEAR                            NOT NULL
mileage     | VARCHAR(7)                      NOT NULL
fuel        | VARCHAR(20)                     NOT NULL
color       | VARCHAR(20)                     NULL
horsepower  | INT                             NULL
plate       | VARCHAR(7) UNIQUE               NOT NULL
condition   | TEXT                            NULL
is_available| TINYINT DEFAULT(1)              NOT NULL
<!-- 1=available 0=sold -->
image       | VARCHAR(255)                    NULL



