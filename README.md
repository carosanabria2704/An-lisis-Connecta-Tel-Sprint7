# Analisis-Connecta-Tel-Sprint7
El objetivo del análisis es evaluar el uso de los clientes de los servicios moviles (llamadas y mensajes de texto) para la empresa Connecta Tel identificando patrones de uso , comportamientos átipicos y evidenciar que segmentos de clientes muestran necesidades diferenciadas para optimizar la estrategia comercial.Evaluamos 4000 clientes hasta el año 2024.

📂 Contenido
Limpieza y analisis de los datos , agrupación por comportamiento de uso, visualización de distribuciones (uso y clientes ) definidos por histogramas, identificación de outliers definidos por boxplot, calculo de limites y quartiles con el metodo IQR , segmentación de clientes e informe ejecutivo.


📊 Datasets fuentes de datos:
1. plans.csv: Catálogo de planes con sus precios y beneficios. /datasets/plans.csv
2. users_latam.csv: Información de cada usuario (datos personales, plan, fecha de registro, churn). /datasets/users_latam.csv
3. usage.csv: Actividad generada por los usuarios: llamadas, mensajes, duración, longitud. /datasets/usage.csv			
<img width="557" height="166" alt="image" src="https://github.com/user-attachments/assets/f4acecca-adc3-439d-9aa0-76e904014973" />

🔄 Etapas del Análisis

Paso 1. Exploración Inicial y Comprensión de los Datos
- Carga y revisión de los datasets proporcionados por ConnectaTel.
- Exploración de la estructura, dimensiones y tipos de datos.
- Evaluación preliminar de la calidad de la información.
- Identificación de posibles inconsistencias y variables clave para el análisis.

Paso 2. Evaluación de Calidad de los Datos
- Identificación y cuantificación de valores nulos.
- Detección de valores sentinels en variables numéricas y categóricas.
- Validación de formatos y rangos de fechas.
- Verificación de patrones de ausencia de datos y análisis de registros MAR (Missing At Random).

Paso 3. Limpieza y Preparación de la Información
- Corrección de valores inconsistentes en variables demográficas.
- Estandarización de registros categóricos y tratamiento de datos faltantes.
- Identificación y corrección de fechas fuera del período de análisis.
- Preparación de los datos para garantizar consistencia y confiabilidad en las etapas posteriores.

Paso 4. Construcción de Métricas de Comportamiento
- Consolidación de la información de uso a nivel de usuario.
- Cálculo de indicadores clave de consumo:
- Cantidad de mensajes enviados.
- Cantidad de llamadas realizadas.
- Total de minutos consumidos en llamadas.
- Integración de métricas de uso con información demográfica y de planes contratados.

Paso 5. Análisis Exploratorio y Detección de Valores Atípicos
- Visualización de distribuciones de variables demográficas y de consumo.
- Comparación de patrones de comportamiento entre planes Básico y Premium.
- Identificación visual de valores atípicos mediante boxplots.
- Aplicación del método IQR para cuantificar y evaluar outliers.
- Determinación del impacto de los valores extremos sobre el análisis y el negocio.

Paso 6. Segmentación de Clientes
- Clasificación de usuarios según nivel de uso del servicio.
- Segmentación por grupos etarios.
- Análisis de patrones de consumo dentro de cada segmento.
- Identificación de perfiles de clientes con potencial estratégico para la compañía.

Paso 7. Generación de Insights y Recomendaciones de Negocio
- Identificación de oportunidades de retención, fidelización y crecimiento.
- Detección de segmentos de alto valor y potencial de monetización.
- Implicaciones para el negocio
- Formulación de recomendaciones para optimizar la oferta de planes y mejorar la experiencia del cliente.

▶️ Cómo ejecutar

- Clona el repositorio
- Coloca los archivos .csv en la carpeta /datasets/
- Abre el notebook S7_Version-Estudiante-Project-ConnectaTel.ipynb
- Ejecuta las celdas en orden


