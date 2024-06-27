 Un DataBase è formato da righe e colonne.
 COLONNE = caratteristiche del dato da memorizzare(struttura)
 RIGHE = rappresenta un dato inserito

 Decido la struttura del mio DataBase, tutti i dati riguardano delle auto usate messe in vendita da un concessionario.

(chiave primaria=identifica in modo univoco ogni riga di dati[colonna])
 
 *id_car = numero
 (attributi = TINYINT, NOTNULL, AUTO_INCREMENT, UNIQUE...NB. essendo la PRIMARY_KEY potrebbe averli di dafault)

(attributi non chiave)
*model_car = string
(attributi = VARCHAR(30), NOTNULL,)

*old_owner = number
(attributi = TINYINT, NULL,) (indico NULL per consentire di non indicare i vecchi propritari)

*km_car = number
(attributi = MEDIUMINT, NOTNULL,) (no TINYINT perchè i km sono numeri piu grandi)

*production_year = data
(attributi = DATE, NOTNULL)

*description_car = string
(attributi = TEXT, NOTNULL,)(text fino a 65535 caratteri)

*price_car = number
(attributi = MEDIUMINT, NOTNULL,)



