# Protocolo DIDÁCTICO de visitas v2.0
REGLAS INVENTADAS. Solo formación. No es una norma sanitaria de Mazana ni una recomendación veterinaria. No procede de las guías FAO o MAPA.

1. Agrupar por Recurso_ID y ordenar Fecha_hora_local. Zona Europe/Madrid.
2. Comparar visitas consecutivas del mismo recurso. Si una visita B va seguida de A, exigir al menos UMBRAL_HORAS. Valor inicial: 48.
3. Limpieza_registrada=no: alerta independiente. Desconocido o vacío: pendiente.
4. Si falta clase o recurso, pendiente. Sin visita previa, indicar que no se conoce la secuencia anterior a la muestra.
5. Cambio de regla para practicar: UMBRAL_HORAS=72. Los nombres A/B son etiquetas inventadas.
6. V02 tiene separación de 24 h. V07 tiene 72 h exactas. V09 tiene 60 h. Con 48 h: V02 alerta y V09 no; con 72 h: ambos alertan, V07 sigue sin alerta de secuencia.
