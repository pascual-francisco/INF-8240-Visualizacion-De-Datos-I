# Unidad 01 - Evaluación Integral de la Unidad I

## Asignatura

**INF-8240 Visualización de Datos I**

## Actividad

**Práctica 1. Evaluación Integral de la Unidad I**

## Descripción General

Esta práctica tiene como propósito integrar y aplicar los principales conceptos estudiados durante la Unidad I de la asignatura. A partir de un caso de estudio empresarial, se desarrolla un análisis completo que combina la comprensión de datos, estadísticas descriptivas, construcción de visualizaciones, interpretación de resultados y comunicación efectiva de hallazgos.

El caso se centra en la empresa ficticia **ComercioDigital RD**, una organización dedicada al comercio electrónico que desea evaluar su desempeño comercial durante un período de seis meses. La dirección necesita comprender la evolución de las ventas, el comportamiento de las reclamaciones y la contribución de sus distintos canales comerciales para apoyar la toma de decisiones.

---

## Contexto del Problema

En entornos empresariales, los datos por sí solos tienen un valor limitado si no son transformados en información útil para la toma de decisiones. La visualización de datos permite identificar patrones, tendencias y oportunidades que pueden pasar desapercibidas al observar únicamente tablas numéricas.

El análisis realizado busca responder preguntas como:

- ¿Cómo evolucionaron las ventas durante el semestre?
- ¿Qué canal comercial genera mayores ingresos?
- ¿Existe alguna relación observable entre ventas y reclamaciones?
- ¿Qué recomendaciones pueden formularse a partir de la evidencia disponible?
- ¿Cuáles son las limitaciones del análisis realizado?

---

## Objetivos de Aprendizaje

Al completar esta práctica, el estudiante será capaz de:

- Identificar y clasificar variables cualitativas y cuantitativas.
- Diferenciar los conceptos de dato, información, conocimiento y decisión.
- Aplicar medidas de tendencia central y dispersión.
- Construir visualizaciones adecuadas para distintos tipos de datos.
- Interpretar gráficos de manera crítica.
- Comunicar hallazgos utilizando principios de storytelling con datos.
- Formular recomendaciones basadas en evidencia.
- Reconocer las limitaciones inherentes a los datos disponibles.

---

## Competencias Evaluadas

### Competencias Técnicas

- Análisis exploratorio de datos.
- Estadística descriptiva.
- Visualización de datos.
- Interpretación de resultados.
- Comunicación analítica.

### Competencias Analíticas

- Pensamiento crítico.
- Toma de decisiones basada en evidencia.
- Identificación de limitaciones y supuestos.
- Evaluación de afirmaciones utilizando datos.

---

## Herramientas Utilizadas

El desarrollo de la práctica se realizó utilizando:

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

Estas herramientas permiten reproducir completamente los cálculos, gráficos e interpretaciones presentados en el análisis.

---

## Contenido de la Práctica

El notebook se encuentra organizado en las siguientes secciones:

### Parte I. Comprensión y análisis de datos

1. Identificación y clasificación de variables.
2. Diferenciación entre dato, información, conocimiento y decisión.
3. Beneficios de la visualización de datos.

### Parte II. Estadística descriptiva

4. Cálculo de medidas descriptivas.
5. Interpretación de la media y análisis del comportamiento de las ventas.

### Parte III. Construcción e interpretación de gráficos

6. Construcción de visualizaciones.
7. Interpretación de gráficos.
8. Análisis de la relación entre ventas y reclamaciones.

### Parte IV. Interpretación crítica y comunicación

9. Evaluación de afirmaciones utilizando evidencia.

### Parte V. Storytelling con datos

10. Desarrollo de una presentación ejecutiva orientada a la gerencia.

### Parte VI. Reflexión final

11. Importancia de la visualización y comunicación en Ciencia de Datos.

---

## Conjuntos de Datos Utilizados

### Conjunto A. Ventas y Reclamaciones Mensuales

| Mes | Ventas | Reclamaciones |
|------|-------:|-------:|
| Enero | 100 | 8 |
| Febrero | 120 | 9 |
| Marzo | 120 | 9 |
| Abril | 140 | 12 |
| Mayo | 160 | 15 |
| Junio | 260 | 25 |

### Conjunto B. Ventas por Canal en Junio

| Canal | Ventas |
|---------|-------:|
| Página web | 100 |
| Aplicación móvil | 80 |
| Redes sociales | 50 |
| Ventas telefónicas | 30 |

---

## Visualizaciones Desarrolladas

Durante la práctica se construyeron las siguientes visualizaciones:

### Gráfico de Líneas

Permite observar la evolución temporal de las ventas y detectar tendencias a lo largo del semestre.

### Gráfico de Barras

Facilita la comparación entre los distintos canales comerciales durante junio.

### Gráfico Circular

Muestra la participación relativa de cada canal dentro del total de ventas del mes.

### Gráfico de Dispersión

Propuesto para analizar la relación entre ventas y reclamaciones mensuales.

---

# Análisis General

## Desempeño Comercial

El análisis de las ventas mensuales muestra un crecimiento sostenido durante el período evaluado. Las ventas aumentaron desde 100 miles de RD en enero hasta 260 miles de RD en junio, registrando el valor más alto del semestre. Aunque entre febrero y marzo las ventas permanecieron constantes, no se observaron disminuciones en ningún momento del período analizado.

Las medidas descriptivas calculadas muestran una media de 150 miles de RD y una mediana de 130 miles de RD. La diferencia entre ambas indica que las ventas excepcionalmente altas observadas en junio ejercen una influencia considerable sobre el promedio general, elevándolo por encima del comportamiento típico de los meses anteriores.

## Comportamiento de las Reclamaciones

Las reclamaciones también presentan una tendencia creciente, pasando de 8 en enero a 25 en junio. Este comportamiento coincide con el incremento de las ventas y podría estar asociado a un mayor volumen de operaciones o clientes atendidos.

Sin embargo, los datos disponibles no permiten concluir que las reclamaciones causen el aumento de las ventas ni que el crecimiento de las ventas provoque directamente el aumento de las reclamaciones. Ambos fenómenos podrían estar relacionados con otros factores no observados.

## Desempeño por Canal Comercial

El análisis de los canales de venta revela que la página web constituye la principal fuente de ingresos de la empresa, generando 100 miles de RD durante junio. La aplicación móvil ocupa el segundo lugar con 80 miles de RD, mientras que las redes sociales y las ventas telefónicas presentan una contribución menor.

La distribución observada sugiere que los canales digitales desempeñan un papel fundamental en la generación de ingresos de ComercioDigital RD.

## Implicaciones para la Gerencia

Los resultados obtenidos sugieren oportunidades para fortalecer los canales digitales con mejor desempeño, especialmente la página web y la aplicación móvil. Asimismo, el incremento de las reclamaciones justifica la revisión de procesos relacionados con atención al cliente, logística y calidad del servicio, con el fin de mantener una experiencia positiva para los usuarios.

La combinación de crecimiento comercial y aumento de reclamaciones indica la necesidad de equilibrar la expansión del negocio con mecanismos adecuados de control y satisfacción del cliente.

---

## Principales Hallazgos

- Las ventas presentan una tendencia creciente durante todo el semestre.
- Junio registra el mayor volumen de ventas del período analizado.
- La página web es el canal con mayor participación en las ventas de junio.
- La aplicación móvil constituye el segundo canal más importante.
- Las reclamaciones aumentan junto con el crecimiento de la actividad comercial.
- Los datos permiten identificar tendencias y asociaciones, pero no relaciones causales.
- El período de análisis es relativamente corto para realizar proyecciones confiables.

---

## Principales Recomendaciones

### 1. Fortalecer el Canal Web

La página web es el canal con mayores ventas y representa la principal fuente de ingresos observada durante el período analizado.

### 2. Potenciar la Aplicación Móvil

La aplicación móvil muestra un desempeño importante y puede representar una oportunidad adicional de crecimiento.

### 3. Investigar las Reclamaciones

Resulta recomendable identificar las causas del aumento de reclamaciones para evitar impactos negativos en la experiencia del cliente.

### 4. Implementar Seguimiento Continuo

La empresa debería monitorear tanto ventas como reclamaciones mediante indicadores periódicos que permitan detectar cambios oportunamente.

### 5. Ampliar la Disponibilidad de Datos

El análisis futuro se beneficiaría de un período más amplio de observación y de variables adicionales relacionadas con clientes, campañas comerciales y operaciones.

---

## Limitaciones del Estudio

- Solo se dispone de seis meses de información.
- Los datos corresponden a una empresa ficticia con fines académicos.
- No existen variables adicionales que permitan explicar completamente los resultados observados.
- No es posible establecer relaciones causales entre ventas y reclamaciones.
- No se dispone de información suficiente para realizar predicciones futuras confiables.

---

## Conclusión

La práctica permitió aplicar de forma integral los conceptos fundamentales de la Unidad I relacionados con análisis descriptivo, visualización de datos e interpretación de resultados. Mediante el uso de estadísticas descriptivas y visualizaciones adecuadas fue posible transformar datos en información útil para la toma de decisiones.

Los resultados muestran una evolución positiva de las ventas y evidencian la importancia de los canales digitales en el desempeño comercial de la empresa. Asimismo, resaltan la necesidad de interpretar los datos de forma crítica, comunicar los hallazgos con claridad y reconocer las limitaciones inherentes a cualquier análisis.

---

## Autor

**Francisco Pascual**

Manufacturing Engineer II  
Estudiante de Ciencia de Datos

## Fecha

Octubre 2026

## Propósito Académico

Material desarrollado exclusivamente con fines educativos como parte de los requisitos de la asignatura **INF-8240 Visualización de Datos I**.
