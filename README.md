# Priorización de hipótesis y análisis de prueba A/B para optimización de ingresos — Proyecto de E-commerce

## ES Español

Descripción del proyecto:

Como Analista de Datos en una gran tienda online, participé en un proyecto estratégico en conjunto con el departamento de marketing para identificar formas de aumentar los ingresos del sitio. El proyecto se dividió en dos fases: priorización de hipótesis mediante frameworks de negocio y análisis estadístico de una prueba A/B real.

## Objetivos principales:

Priorizar hipótesis de negocio para maximizar impacto y eficiencia en la implementación.

Ejecutar y analizar una prueba A/B para evaluar la efectividad de posibles mejoras.

Detectar anomalías, validar hipótesis estadísticas y tomar decisiones fundamentadas.

## Fase 1: Priorización de hipótesis

Se trabajó con un conjunto de nueve hipótesis que buscaban mejorar métricas clave del negocio (conversiones, ingresos, experiencia del usuario).

## T#areas realizadas:

Aplicación de los frameworks ICE (Impact, Confidence, Effort) y RICE (Reach, Impact, Confidence, Effort).

Cálculo de puntajes y ordenamiento de hipótesis según cada método.

Comparación y análisis crítico de la diferencia en las prioridades obtenidas por ICE y RICE, destacando cómo el alcance (Reach) puede cambiar la perspectiva de valor de una hipótesis.

## Fase 2: Análisis del test A/B

Utilizando los datos de comportamiento de usuarios, ingresos y visitas para los grupos de prueba A y B, se realizó un análisis detallado de la prueba A/B.

## Análisis exploratorio y estadístico:

Visualización del ingreso acumulado y tamaño promedio de pedido por grupo.

Análisis de la diferencia relativa acumulada en métricas clave (ingresos, conversiones).

Cálculo y visualización de tasas de conversión diarias.

Identificación de valores atípicos en número de pedidos y monto de pedidos por usuario mediante percentiles (95 y 99).

Evaluación del impacto de anomalías en los resultados generales.

## Pruebas estadísticas realizadas:

Comparación de tasas de conversión y tamaños promedio de pedido entre los grupos A y B, tanto con datos brutos como con datos filtrados (excluyendo outliers).

Uso de pruebas de hipótesis (Mann-Whitney U test) para determinar la significancia estadística de las diferencias observadas.

## Herramientas utilizadas:

Python (pandas, numpy, scipy, matplotlib, seaborn)

Jupyter Notebook

Análisis estadístico y visualización de datos

## Resultados clave:

El grupo B mostró inicialmente métricas superiores, pero estas diferencias no fueron consistentemente significativas tras eliminar valores atípicos.

La decisión final fue detener la prueba y concluir que no hay diferencia estadísticamente significativa entre los grupos A y B.

La priorización con RICE reveló oportunidades más eficientes que con ICE, permitiendo una mejor asignación de recursos para futuras pruebas.


# Hypothesis prioritization and A/B testing analysis for revenue optimization — E-commerce project

## US English 

Project description:

As a Data Analyst at a large online store, I participated in a strategic project in conjunction with the marketing department to identify ways to increase the site's revenue. The project was divided into two phases: hypothesis prioritization using business frameworks and statistical analysis of a real A/B test.

## Main objectives:

Prioritize business hypotheses to maximize impact and efficiency in implementation.

Execute and analyze an A/B test to evaluate the effectiveness of possible improvements.

Detect anomalies, validate statistical hypotheses, and make informed decisions.

## Phase 1: Hypothesis prioritization

We worked with a set of nine hypotheses that sought to improve key business metrics (conversions, revenue, user experience).

## Tasks performed:

Application of the ICE (Impact, Confidence, Effort) and RICE (Reach, Impact, Confidence, Effort) frameworks.

Calculation of scores and ranking of hypotheses according to each method.

Comparison and critical analysis of the difference in priorities obtained by ICE and RICE, highlighting how reach can change the value perspective of a hypothesis.

## Phase 2: A/B test analysis

Using user behavior, revenue, and visit data for test groups A and B, a detailed analysis of the A/B test was performed.

## Exploratory and statistical analysis:

Visualization of cumulative revenue and average order size by group.

Analysis of the cumulative relative difference in key metrics (revenue, conversions).

Calculation and visualization of daily conversion rates.

Identification of outliers in the number of orders and order amount per user using percentiles (95 and 99).

Evaluation of the impact of anomalies on overall results.

## Statistical tests performed:

Comparison of conversion rates and average order sizes between groups A and B, using both raw data and filtered data (excluding outliers).

Use of hypothesis tests (Mann-Whitney U test) to determine the statistical significance of the observed differences.

## Tools used:

Python (pandas, numpy, scipy, matplotlib, seaborn)

Jupyter Notebook

Statistical analysis and data visualization

## Key results:

Group B initially showed superior metrics, but these differences were not consistently significant after removing outliers.

The final decision was to stop the test and conclude that there was no statistically significant difference between groups A and B.

Prioritization with RICE revealed more efficient opportunities than with ICE, allowing for better resource allocation for future testing.
