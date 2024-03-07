Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario


  # "cars" table

|FIELD|TYPE|ATTRIBUTES|INDEXS|
| ------ | ---- | ---------- | ------ |
| telaio| INT| AUTO_INCREMENT UNIQUE| PRIMARY KEYS|
|colore|VARCHAR(15)
|marca|VARCHAR(20)
|cilindrata|DECIMAL(4,3)
|anno| YEAR
|immatricolazione| DATE