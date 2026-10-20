# Reglas de práctica - DATOS FICTICIOS

No son procedimientos operativos de Mazana. No generar pedidos, rutas ejecutables, decisiones sanitarias ni comunicaciones.

## Logística
- Verificar cada carga asignada por separado: vehículo existente, misma familia y toneladas <= capacidad.
- Sin vehículo: pendiente de asignación. Una asignación ausente no demuestra que no exista capacidad disponible.
- Mostrar retrasos positivos registrados; no inferir duración de trayecto.
- No se aportan ventanas, secuencias, descansos ni disponibilidad temporal. No demostrar optimalidad o viabilidad global.

## Stock y reposición
- Las cantidades son unidades genéricas de artículo ficticio; no son medicamentos ni dosis.
- Stock objetivo = consumo diario * (plazo de entrega + días de seguridad).
- Posición disponible = stock + en pedido.
- Propuesta = ceil(max(0, objetivo - posición)).
- Cobertura = stock actual / consumo diario (sin incluir en pedido).
- Consumo ausente o <= 0: cobertura, objetivo y propuesta pendientes. No convertir vacío en cero.
- Stock, en pedido, plazo o seguridad negativos, o campos requeridos ausentes: fila pendiente. No estimarlos.
- No hay lotes de compra, caducidades, reservas, mermas ni decisiones de prescripción en este ejercicio.

## Costes
- Todos los importes son ficticios y no incluyen IVA, impuestos u otros costes.
- Coste por fila = toneladas * precio en euros/t + transporte TOTAL de la fila.
- Desviación = real - presupuesto. Porcentaje = desviación / presupuesto * 100, si presupuesto no es cero.
- Escenario = toneladas reales * precio real * 1,05 + transporte real sin cambio.
- Calcular antes de redondear. Mostrar euros con dos decimales y unidades visibles.

## Ubicaciones
- Coordenadas sintéticas para dibujar puntos, sin equivalencia a instalaciones de Mazana.
- Los grupos son etiquetas didácticas. No son clasificaciones sanitarias.
- Las líneas son conexiones esquemáticas, sin cálculo de carretera, distancia o tiempo.
