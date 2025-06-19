# Priorización de hipótesis y análisis de prueba A/B para optimización de ingresos — Proyecto de E-commerce

## ES Español

**Rol:** Analista de Datos  
**Herramientas:** Python (pandas, numpy, scipy, matplotlib, seaborn), Jupyter Notebook

### Descripción del proyecto  
Como Analista de Datos en una tienda online, participé en un proyecto estratégico junto con marketing para aumentar los ingresos. El proyecto constó de dos fases: priorización de hipótesis usando frameworks de negocio y análisis estadístico de una prueba A/B real.

### Objetivos principales  
- Priorizar hipótesis para maximizar impacto y eficiencia en implementación.  
- Ejecutar y analizar prueba A/B para evaluar mejoras.  
- Detectar anomalías, validar hipótesis estadísticas y tomar decisiones basadas en datos.

### Fase 1: Priorización de hipótesis  
Se trabajó con nueve hipótesis para mejorar métricas clave (conversiones, ingresos, experiencia de usuario).

#### Tareas realizadas  
- Aplicación de frameworks ICE (Impact, Confidence, Effort) y RICE (Reach, Impact, Confidence, Effort).  
- Cálculo de puntajes y ordenamiento de hipótesis según cada método.  
- Comparación crítica entre prioridades ICE vs. RICE, mostrando cómo el alcance (Reach) cambia la percepción de valor.

### Fase 2: Análisis del test A/B  
Análisis detallado de datos de usuarios, ingresos y visitas para grupos A y B.

#### Análisis exploratorio y estadístico  
- Visualización de ingresos acumulados y tamaño promedio de pedido por grupo.  
- Análisis de diferencia relativa acumulada en ingresos y conversiones.  
- Cálculo y visualización de tasas de conversión diarias.  
- Identificación de outliers en número y monto de pedidos (percentiles 95 y 99).  
- Evaluación del impacto de anomalías en resultados globales.

#### Pruebas estadísticas  
- Comparación de tasas de conversión y tamaño promedio de pedido entre grupos A y B, con datos brutos y filtrados.  
- Uso de Mann-Whitney U test para validar diferencias estadísticamente significativas.

### Herramientas utilizadas  
- Python (pandas, numpy, scipy, matplotlib, seaborn)  
- Jupyter Notebook  
- Análisis estadístico y visualización de datos

### Resultados clave  
- El grupo B mostró métricas superiores inicialmente, pero diferencias no fueron significativas tras eliminar outliers.  
- Se decidió detener la prueba concluyendo ausencia de diferencias estadísticamente significativas.  
- La priorización con RICE mostró oportunidades más eficientes que ICE, facilitando mejor asignación de recursos para futuras pruebas.

---

# Hypothesis prioritization and A/B testing analysis for revenue optimization — E-commerce project

## US English

**Role:** Data Analyst  
**Tools:** Python (pandas, numpy, scipy, matplotlib, seaborn), Jupyter Notebook

### Project description  
As a Data Analyst at a large online store, I participated in a strategic project with marketing to increase site revenue. The project had two phases: hypothesis prioritization using business frameworks and statistical analysis of a real A/B test.

### Main objectives  
- Prioritize business hypotheses to maximize impact and efficiency.  
- Execute and analyze an A/B test to evaluate improvements.  
- Detect anomalies, validate statistical hypotheses, and make informed decisions.

### Phase 1: Hypothesis prioritization  
Worked with nine hypotheses targeting key business metrics (conversions, revenue, user experience).

#### Tasks performed  
- Applied ICE (Impact, Confidence, Effort) and RICE (Reach, Impact, Confidence, Effort) frameworks.  
- Calculated scores and ranked hypotheses per method.  
- Compared and critically analyzed priority differences between ICE and RICE, highlighting the effect of reach.

### Phase 2: A/B test analysis  
Detailed analysis of user behavior, revenue, and visits for test groups A and B.

#### Exploratory and statistical analysis  
- Visualized cumulative revenue and average order size by group.  
- Analyzed cumulative relative difference in revenue and conversions.  
- Calculated and visualized daily conversion rates.  
- Identified outliers in order count and amount per user using 95th and 99th percentiles.  
- Assessed anomaly impact on overall results.

#### Statistical tests performed  
- Compared conversion rates and average order sizes between groups A and B on raw and filtered data.  
- Used Mann-Whitney U test to determine statistical significance.

### Tools used  
- Python (pandas, numpy, scipy, matplotlib, seaborn)  
- Jupyter Notebook  
- Statistical analysis and data visualization

### Key results  
- Group B initially showed better metrics, but differences lost significance after removing outliers.  
- Test was stopped concluding no statistically significant difference between groups.  
- RICE prioritization revealed more efficient opportunities than ICE, enabling better resource allocation for future tests.
