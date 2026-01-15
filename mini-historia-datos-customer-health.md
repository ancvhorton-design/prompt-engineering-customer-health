# Mini-historia con datos: Customer Health

## Contexto del dataset
Imaginemos un conjunto de datos de clientes de una empresa de logística, donde se registran semanalmente las métricas de: puntualidad de entregas (%), NPS, número de quejas abiertas y pedidos rechazados (%). El objetivo es monitorear el comportamiento de los clientes y detectar señales tempranas de riesgo.

## Pregunta guía
¿Cómo se comporta la satisfacción y el cumplimiento operativo de los clientes a lo largo de las últimas 8 semanas?

## Hallazgo descriptivo
Se observa que la **puntualidad en entregas ha disminuido gradualmente del 96% al 85%**, mientras que las quejas abiertas se concentran en un pequeño grupo de clientes recurrentes. El NPS se mantiene relativamente estable pero con tendencia levemente negativa en la última semana.

## Propuesta de visualización
- **Gráfica de líneas** para mostrar la evolución de puntualidad y NPS a lo largo de las semanas.
  - Eje X: Semanas (1 a 8)  
  - Eje Y: Porcentaje de puntualidad y valor de NPS  
- **Gráfico de barras** para mostrar el número de quejas por cliente.
  - Eje X: Clientes  
  - Eje Y: Número de quejas abiertas

## Mini reflexión
Los datos muestran tendencias claras, pero no permiten afirmar causalidad; además, es importante considerar posibles errores de registro y que un pequeño grupo de clientes puede sesgar las métricas generales.

## Prompt para IA
