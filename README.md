//Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un ocncessionario.

## Table name: Auto

## Table columns: 

- ID [Bigint], PRIMARY_KEY, AUTO_INCREMENT, NOTNULL, UNIQUE
- Codice Telaio [Bigint] NOTNULL, UNIQUE
- Targa [Char(7)] NOTNULL, UNIQUE
- Modello [Varchar(100)] NOTNULL
- Marca [Varchar(100)] NOTNULL
- Categoria [Varchar(100)]
- Prezzo [Double(10,2)] NOTNULL
- Potenza [Float(5,1)] NOTNULL
- Cilindrata [Float(5,1)] NOTNULL
- Kilowatt [Float(6,2)]
- Carburante [Varchar(50)] NOTNULL
- Anno produzione [Year] NOTNULL
- Chilometraggio [Mediumint] NOTNULL
- Cambio [Varchar(50)]
- Neopatentati [Char(2)] NOTNULL
- Lunghezza [Smaillint]
- Larghezzza [Smaillint]
- Altezza [Smaillint]
- Peso [Smaillint]
- Colore [Varchar(100)]
- Optionals [Text]
- Proprietari Precedenti [Tintint]
