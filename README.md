# AUTO USATE DATABASE

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

|                     |   macchine_usate   |                                       |
| :------------------ | :----------------: | :-----------------------------------: |
| id                  |       INT          |       AUTO_INCREMENT,NOT NULL - PK    |
| marca               |    VARCHAR(20)     |               NOT-NULL                |
| modello             |    VARCHAR(30)     |               NOT-NULL                |
| chilometraggio      |     MEDIUMINT      |               NOT-NULL                |
| anno_di_costruzione |       YEAR         |                 NULL                  |
| identificativo_telaio |  VARCHAR(17)     |           NOT-NULL, UNIQUE            |
| targa_autoveicolo   |    VARCHAR(15)     |           NOT-NULL, UNIQUE            |
| colore              |    VARCHAR(30)     |                 NULL                  |
| prezzo              |     DECIMAL(10,2)  |               NOT-NULL                |
| porte               |      TINYINT       |                 NULL                  |
| cambio              |    VARCHAR(20)     |               NOT-NULL                |
| carburante          |    VARCHAR(20)     |               NOT-NULL                |
