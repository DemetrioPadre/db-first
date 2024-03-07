Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario


  # "cars" table

|FIELD|TYPE|ATTRIBUTES|INDEXS|
| ------ | ---- | ---------- | ------ |
| telaio| INT| AUTO_INCREMENT UNIQUE NOT_NULL| PRIMARY KEYS|
|colore|VARCHAR(15)|DEFAULT(0)
|marca|VARCHAR(20)|NOT_NULL
|cilindrata|DECIMAL(4,3)|NOT_NULL, UNSIGNED|
|anno| YEAR| NOT_NULL, UNSIGNED|
|immatricolazione| DATE| NOT_NULL|
|km|INT|AUTO_INCREMENT, UNSIGNED|
|condizioni| TEXT| NULL|
|ruota di scorta|TINYINT|NULL|