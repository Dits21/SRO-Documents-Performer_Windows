Categorias Obligatorias Explicado:
	Notese que:
		Actualmente son desconocidos todos los tipos de reclamo.
		Actualmente son desconocidos todos los tipos de Categorias.
		Se llego a mencionar por la analista de negocio en la sesion de transferencia de conocimiento que en la videodocumentacion del proceso se menciona que el robot solo procesara un tipo de reclamo.
			Sin embargo por precaucion y pensando a futuro, crearemos un template flexible para varios tipos de reclamo.
		Actualmente en la arquitectura no se tiene contemplado en que momento del proceso se podra distinguir que tipo de reclamo el robot esta procesando.
			Debido al punto anterior, utilizaremos un tipo de reclamo Quemado en el codigo para siempre seleccionar el tipo de reclamo dictado por el analista de negocio. (hasta que se solvente el punto previo.)
	Instrucciones:
		En el archivo de reglas de negocio se encuentra la hoja de calculo "Categorias Obligatorias" un template, el cual debera ser reemplazado por data real por el desarrollador con la informacion provista por el analista de negocio.
		Segun las reglas de negocio compartidas, las categorias de reclamo obligatorias varian dependiendo del tipo de reclamo.
		Por lo que dependiendo de la columna de reclamo, se colocara el valor (1) en la fila de la categoria para indicar que dicha categoria es obligatoria en el reclamo.