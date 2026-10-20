# Prompts de las dinámicas de Mazana
20/10/2026 · Datos de operación ficticios. Guías externas con fuentes y fecha.

## INV01. Logística de animales, pienso y cereal
Archivos: Brief_Mazana_FICTICIO.md, Logistica_FICTICIA.csv, Vehiculos_FICTICIOS.csv

### INV01. Investigar logística

```text
Actúa como investigador de operaciones para una empresa del sector de alimentación animal y producción porcina. Usa el brief ficticio adjunto para entender el ejercicio, no como evidencia de la operación real de Mazana.

Pregunta: ¿qué oportunidades y condiciones existen para mejorar pedidos, cargas, recorridos repetitivos y coordinación de transporte, distinguiendo animales, pienso y cereal?

Busca fuentes primarias publicadas en los últimos 24 meses hasta el 20/10/2026. Puedes añadir fundamentos anteriores si identificas su fecha. Prioriza documentación técnica, publicaciones originales y casos con metodología visible. Analiza capacidades, ventanas horarias, compatibilidad de cargas, limpieza, restricciones sanitarias aprobadas, disponibilidad y calidad de datos. No inventes reglas sanitarias.

Entrega: 1) síntesis ejecutiva de dos páginas; 2) tabla de 6-8 fuentes con fecha, enlace, evidencia y límite; 3) datos mínimos de un piloto; 4) criterios para comparar una propuesta con el plan actual. Separa optimización matemática, predicción e IA generativa. No atribuyas ahorros, implantaciones, proveedores o sistemas a Mazana sin fuente interna. Marca datos ausentes.
```

## INV02. Alimentación porcina e investigación comercial
Archivos: Brief_Mazana_FICTICIO.md

### INV02. Investigar alimentación y mercado

```text
Investiga tendencias y aplicaciones documentadas relevantes para una compañía de piensos y producción porcina en España. Fecha de corte: 20/10/2026.

Compara tres líneas: previsión del consumo y aprovisionamiento; trazabilidad y calidad de materias primas; uso de agentes para apoyar al equipo comercial B2B con preparación de visitas, preguntas de descubrimiento y borradores basados en fuentes.

Prioriza fuentes originales de los últimos 24 meses, organismos públicos, FAO, EFSA, centros de investigación y estudios publicados. Identifica por separado referencias fundacionales anteriores. No conviertas publicidad en evidencia de eficacia ni supongas que una noticia demuestra presupuesto del cliente.

Entrega una matriz: necesidad, caso documentado, fuente/fecha, datos que requiere, resultado medido si existe, límites y pregunta para el responsable del área. Cierra con cinco hipótesis de piloto para contrastar y un ejemplo de guion de visita comercial. No formules raciones individuales, no recomiendes tratamientos y no inventes precios, clientes o capacidades actuales de Mazana.
```

## NBL01. De una guía de piensos a una checklist
Archivos: FAO_IFIF_Buenas_Practicas_Piensos_2014.pdf

### NBL01. Consultar la guía de piensos

```text
Usa exclusivamente «Buenas prácticas para la industria de piensos», FAO e IFIF, edición española de 2014, que he cargado.

Trabaja la sección 3 sobre producción, procesamiento, almacenamiento, transporte y distribución. Prepara una checklist de formación de 12 puntos para recepción de materias primas y expedición de pienso. Para cada punto indica qué revisar, evidencia o registro que buscar y cita que permita abrir el pasaje de la fuente.

Separa lo que dice el manual de las preguntas que propones para una fábrica concreta. No inventes límites críticos, temperaturas o frecuencias que no aparezcan. No declares cumplimiento legal actual a partir de un manual de 2014. Añade cinco preguntas de comprensión y su referencia. Si un campo no consta, indícalo.
```

## NBL02. Preparar una visita de bioseguridad
Archivos: MAPA_Bioseguridad_Porcino_Intensivo.pdf

### NBL02. Preparar la visita con citas

```text
Trabaja solo con «Guía Bioseguridad externa frente a fauna en porcino intensivo», MAPA, NIPO 003-26-023-1, cita de 2026.

Prepara una ficha de formación dividida en antes, durante y después de la visita. Incluye cuatro preguntas por bloque, qué observación o registro ayudaría a responderlas y una cita que abra el apartado de origen.

Distingue recomendación del documento, evidencia que se observa y dato pendiente. Mantén el ámbito de bioseguridad externa frente a fauna; no presentes la guía como cobertura de todos los riesgos de una explotación. No diagnostiques enfermedades ni asignes un estado sanitario real. No introduzcas umbrales de 48 o 72 horas: pertenecen a otro ejercicio inventado y no a esta fuente. Cierra con las decisiones que requerirían revisión del responsable veterinario.
```

## W01. Agente 1. Parte de logística
Archivos: Logistica_FICTICIA.csv, Vehiculos_FICTICIOS.csv, Reglas_practica.md

### W01A. Revisar cargas

```text
Con Logistica_FICTICIA.csv, Vehiculos_FICTICIOS.csv y Reglas_practica.md, revisa cada carga asignada. Comprueba vehículo, familia compatible y toneladas frente a capacidad. Separa retrasos registrados, campos ausentes y restricciones no aportadas. Entrega una tabla con ID, dato fuente, cálculo, incidencia y pregunta pendiente, seguida de un parte de cinco líneas. No inventes tiempos ni disponibilidad y no declares una planificación óptima. Conserva las entradas.
```

### W01B. Preparar el siguiente paso

```text
Con las incidencias ya verificadas, prepara un borrador de parte para el responsable de logística y una lista de decisiones pendientes. Para L03 muestra el cálculo de exceso de carga y el retraso conocido. Para L04 pide confirmar asignación sin afirmar que no existe capacidad. Propón dos vías para revisar, con los datos que exigiría cada una. No asignes vehículos ni envíes mensajes. Guarda el parte como documento editable.
```

## W02. Agente 2. Compras y reposición
Archivos: Stock_FICTICIO.csv, Reglas_practica.md

### W02A. Calcular reposición

```text
Lee Stock_FICTICIO.csv y aplica la regla de Reglas_practica.md: objetivo = consumo diario × (plazo + seguridad); posición = stock + en pedido; propuesta = máximo entre 0 y objetivo menos posición, redondeado hacia arriba. Muestra cobertura de stock actual y operación por ID. Un consumo ausente o no positivo queda pendiente. No sustituyas vacíos por cero. Devuelve una hoja editable con entradas conservadas y fórmulas visibles. No emitas pedidos.
```

### W02B. Borrador para validar compras

```text
Usando únicamente la propuesta revisada, redacta un borrador interno para validar reposiciones. Separa cantidades calculadas, artículos pendientes y datos que faltan para decidir: unidades de compra, disponibilidad, caducidad si procede, precio y plazo confirmados. No los inventes. Usa IDs de artículos genéricos, sin recomendaciones clínicas o de dosificación. No escribas en el ERP ni envíes el borrador.
```

## W03. Agente 3. Correo y proveedores
Archivos: Correos_FICTICIOS.txt

### W03A. Leer el buzón de formación

```text
Lee completos los cuatro mensajes de Correos_FICTICIOS.txt. Corte: 20/10/2026 a las 09:00 Europe/Madrid. Prepara una tabla con ID del mensaje, asunto, petición, plazo que conste, dato faltante y siguiente paso propuesto. Distingue una oferta de una compra aceptada y un retraso comunicado de una nueva entrega confirmada. No inventes adjuntos ni responsables. No envíes, archives ni modifiques mensajes.
```

### W03B. Comparar y preparar respuesta

```text
Compara E01 y E02 para 240 unidades de M01. Calcula importes de mercancía, diferencia y plazos comunicados. Deja transporte, impuestos y condiciones de pago como pendientes. Redacta dos borradores: uno al responsable de compras con la comparación y otro al proveedor elegido solo como propuesta, solicitando los datos ausentes. No selecciones una oferta en firme, no aceptes condiciones y no envíes nada. Usa solo direcciones .invalid del ejercicio si necesitas identificarlas.
```

## W04. Agente 4. Albarán con imagen
Archivos: Albaran_ALB040_FICTICIO.png, Pedidos_Albaran_FICTICIOS.csv

### W04A. Extraer y contrastar

```text
Lee la imagen Albaran_ALB040_FICTICIO.png y contrástala con Pedidos_Albaran_FICTICIOS.csv. Extrae albarán, pedido, producto, fecha, cantidad, unidad, precio unitario e importe, conservando el texto leído. No completes datos poco legibles. Normaliza kg a toneladas y €/kg a €/t mostrando las operaciones. Entrega la comparación por ID y la diferencia. No supongas aceptación, firma, pago o una segunda entrega.
```

### W04B. Documentar la incidencia

```text
Con los campos revisados contra la imagen, prepara una ficha de incidencia y un borrador de respuesta a recepción. Incluye pedido, albarán, cantidad pedida, cantidad del documento, diferencia en toneladas e importe equivalente al precio del ejercicio. Explica qué no consta y qué confirmaríamos antes de decidir. Guarda una tabla editable y un resumen de cinco líneas. No envíes comunicaciones ni modifiques registros reales.
```

## VC01. Aplicación de mínimos y reposición
Archivos: Stock_FICTICIO.csv, Reglas_practica.md

### VC01A. Construir el prototipo

```text
Construye un prototipo local sencillo para la tabla Stock_FICTICIO.csv aplicando solo Reglas_practica.md. Antes de editar, explica entradas, fórmulas, interfaz, guardado y pruebas. Después crea una aplicación pequeña que importe CSV y muestre objetivo, posición, cobertura y propuesta por ID. Los vacíos y datos negativos se señalan sin inventarlos. Incluye «Incluir en pedido», activado por defecto. Conserva los archivos originales. No instales servicios, no conectes el ERP y no publiques. Comprueba M01=240, M03=20 y M04 pendiente. Dime cómo abrirla y qué has probado.
```

### VC01B. Cambiar y comprobar la regla

```text
Modifica solo el control «Incluir en pedido»: cuando esté desactivado, la posición usa únicamente stock actual; al activarlo, suma en pedido. Mantén los demás criterios y datos. Prueba M01: activado 240, desactivado 340; M03: 20 y 60. M04 sigue pendiente. Añade la regla activa junto a la tabla y una prueba de consumo cero. No añadas compra automática, conexiones o publicación.
```

## VC02. Aplicación de revisión de visitas
Archivos: Visitas_FICTICIAS.csv, Protocolo_Visitas_FICTICIO.md

### VC02A. Construir el revisor

```text
Crea un prototipo local que lea Visitas_FICTICIAS.csv y aplique exclusivamente Protocolo_Visitas_FICTICIO.md. Son reglas inventadas para formación, no una valoración sanitaria. Agrupa por recurso, ordena fechas Europe/Madrid y compara visitas consecutivas. Añade un umbral editable con valor inicial 48 h para B→A. Separa alerta de secuencia, limpieza y pendiente. Muestra ID previo, ID de llegada, horas y regla. No publiques ni conectes sistemas. Comprueba V02, V04, V05, V07 y V09 y explica los límites de la muestra.
```

### VC02B. Cambiar el umbral y probar la frontera

```text
Cambia el umbral de 48 a 72 horas usando el control de la aplicación, sin alterar el CSV. Comprueba que V09, con 60 h, pasa de no tener alerta de secuencia a tenerla; V02 mantiene su alerta y V07, con 72 h exactas, no se alerta. La condición de alerta es horas < umbral. Conserva las alertas de limpieza y los pendientes. Deja visible «Regla didáctica, no protocolo veterinario». No infieras contagios o riesgos sanitarios reales.
```

## XL01. Presupuesto, real y coste por tonelada
Archivos: Produccion_Piensos_Mazana_FICTICIA.xlsx

### XL01. Analizar el Excel abierto

```text
Trabaja sobre esta copia de Produccion_Piensos_Mazana_FICTICIA.xlsx. Primero explica las hojas Resumen, Produccion y Escenario y localiza las entradas y fórmulas. El periodo es enero-septiembre de 2026 y todas las cifras son ficticias.

Revisa presupuesto frente a real: volumen, ventas, materias primas, fabricación, transporte, coste variable y margen de contribución. En Produccion cada fila representa mes, familia y tipo Presupuesto/Real; no sumes ambos tipos como si fueran un total operativo. Cita celdas y comprueba las fórmulas.

Prepara cinco conclusiones con cifra, operación y límite. Comprueba dos filas y los totales de Resumen. Explica por qué el coste puede subir por volumen y por coste unitario. No atribuyas causas a contratos o proveedores sin datos. No confundas margen de contribución con beneficio neto y conserva el original.
```

## XL02. Simular precio y volumen
Archivos: Produccion_Piensos_Mazana_FICTICIA.xlsx

### XL02. Modificar el escenario

```text
En la hoja Escenario de esta copia, modifica únicamente las entradas B5:B7: materias primas +8 %, volumen +5 % y precio de venta 0 %. Conserva Produccion y las relaciones de fórmulas. Otros costes variables unitarios permanecen constantes; al subir volumen también sube su importe total.

Comprueba ventas, coste variable y margen simulados y compáralos con el real ficticio de Resumen. Cita celdas, explica las operaciones y prepara un gráfico sencillo o un comentario breve para dirección. No interpretes esta simulación sobre la muestra como previsión aprobada. Después prueba 0/0/0: debe reproducir la base. Si falta un parámetro, muestra Pendiente, no un cero que parezca real. Guarda una versión identificada con los supuestos aplicados.
```

## IMG01. Infografía del flujo logístico
Archivos: Flujos_Visuales_FICTICIOS.md, Guia_general_Mazana.pdf

### IMG01. Generar el flujo visual

```text
Crea una infografía horizontal 16:9, 1920×1080, para formación en logística de alimentación animal. Usa el documento Flujos_Visuales_FICTICIOS.md como contenido y la guía adjunta como referencia estética.

Representa seis pasos de izquierda a derecha: «Pedido», «Validación», «Planificación», «Carga», «Entrega», «Incidencias». Bajo ellos, tres carriles identificables: «Animales», «Pienso» y «Cereal». Muestra un desvío de vuelta a revisión cuando faltan datos o la carga supera la capacidad. Usa iconos técnicos sencillos de camión, silo, documento y verificación. Evita escenas que puedan confundirse con instalaciones reales.

Fondo blanco y marfil #F4F2EF, texto #202020, acentos #CB001B. Titulares serif inspirados en IBM Plex Serif y etiquetas monoespaciadas; rótulos breves y legibles. Incluye «Ejemplo de formación». No añadas cifras de ahorro, límites sanitarios, marcas o maquinaria específica de Mazana. Mantén espacio y contraste para proyectar. Revisa el texto generado.
```

## IMG02. Ficha técnica del proceso de pienso
Archivos: Flujos_Visuales_FICTICIOS.md, Guia_general_Mazana.pdf

### IMG02. Generar la lámina técnica

```text
Genera una lámina técnica horizontal 16:9 para explicar, de forma simplificada, un proceso de fabricación y expedición de pienso. Usa Flujos_Visuales_FICTICIOS.md como fuente del esquema. No representa una fábrica real de Mazana.

Organiza seis módulos: «Recepción», «Revisión», «Almacenamiento», «Dosificación y mezcla», «Acondicionamiento, si procede» y «Expedición». En cada módulo muestra un icono de equipo genérico, la entrada/salida y un pequeño documento de trazabilidad. Diferencia el flujo de material del flujo de registros con líneas de estilo distinto y leyenda. Representa los pasos de revisión como preguntas, no como controles sanitarios validados.

Estética editorial de la guía: blanco, marfil #F4F2EF, negro #202020 y rojo #CB001B; titulares serif y etiquetas monoespaciadas. Usa pocos rótulos y espacio generoso. No inventes recetas, porcentajes de ingredientes, tiempos, temperaturas o límites críticos. Incluye «Esquema didáctico simplificado». Deja los textos largos para una capa editable posterior.
```
