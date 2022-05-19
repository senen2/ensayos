Estructura

Oraciones
	Frases
		Frase Sujeto
			Sujetos
		Verbo
			Verbos
		Predicado
			Sujetos
Además, un sujeto de una frase puede estar en una frase anterior (o posterior?)

Algoritmo

Se busca el sujeto
	Aparece sujeto
		Se suman todos los sujetos y adjetivos que se encuentren.
			Se vinculan con las preposiciones?
	Aparece un verbo
		Se sube la frase del sujeto
			Se trata de vincular con el predicado de la frase anterior
			Se inicia la frase
				Se inicia la frase con el nodo de inicio de frase
		Se adicionan todas las palabras que se encuentren
	Aparece sujeto
		Se suman todos los sujetos y adjetivos que se encuentren.
			Se vinculan con las preposiciones?
	Aparece puntuación 
		Se sube el verbo con el predicado
		Se cierra la frase con el nodo de final de frase
		
