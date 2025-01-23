# Proyecto1_Tarifas_Telefonicas

El objetivo de este proyecto fue determinar cuál de las dos tarifas de prepago ofrecidas por Megaline, **Surf** y **Ultimate**, genera más ingresos. La empresa busca usar esta información para optimizar su presupuesto publicitario. Para ello, se analizaron datos de 500 clientes, incluyendo llamadas, mensajes, uso de internet, y detalles de las tarifas durante 2018.

### Datos disponibles

Se proporcionaron cinco tablas con información sobre:
1. **Llamadas**: duración y fechas.
2. **Mensajes**: cantidad y fechas.
3. **Internet**: datos utilizados y fechas.
4. **Tarifas**: detalles de los planes Surf y Ultimate.
5. **Usuarios**: perfil y plan asignado.

### Procesos realizados

1. **Preparación de los datos**:
   - Conversión de tipos de datos (fechas y columnas de ID).
   - Relleno de valores ausentes en columnas relevantes.
   - Eliminación de duplicados.

2. **Enriquecimiento de los datos**:
   - Unión de tablas para relacionar usuarios con sus actividades.
   - Conversión de MB a GB para facilitar el análisis.

3. **Agregación de datos por usuario**:
   - Cálculo mensual de llamadas, mensajes, minutos y tráfico de internet por usuario.

### Próximos pasos
Se analizaron los datos agregados para comparar ingresos generados por cada tarifa y determinar cuál es más rentable.
