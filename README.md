Análisis y Predicción de Ingresos Diarios

Descripción del Proyecto

Este proyecto tiene como objetivo analizar y predecir los ingresos diarios totales de una organización a partir de datos almacenados en un archivo CSV. Se emplean técnicas de análisis exploratorio, detección de patrones y tendencias, así como el desarrollo de modelos predictivos utilizando diferentes enfoques de machine learning.

Estructura del Proyecto

Análisis Exploratorio de Datos (EDA):

Identificación de tendencias y estacionalidad en los ingresos diarios.

Detección de outliers y evaluación de su impacto en las ventas.

Modelado Predictivo:

Regresión lineal múltiple: Para modelar las relaciones lineales entre las variables predictoras (cantidad, precio, descuento y región) y los ingresos diarios.

Modelos no lineales: Uso de Random Forest y Gradient Boosting para capturar relaciones más complejas.

Evaluación de Modelos:

Uso de métricas como el MAE y .

Análisis de residuales para evaluar el ajuste del modelo.

Tecnologías Utilizadas

Python: Lenguaje principal para el análisis y modelado.

Bibliotecas de Python:

pandas y numpy: Para la manipulación y análisis de datos.

matplotlib y seaborn: Para la visualización de datos.

scikit-learn: Para la implementación de los modelos predictivos y la evaluación.

statsmodels: Para descomponer series temporales.

SQLite: Para almacenar y gestionar los datos si es necesario.

Visual Studio Code: Editor de código.

Requisitos Previos

Instalar Python y dependencias:

Crear un entorno virtual (opcional):

python -m venv venv
source venv/bin/activate  # En Linux/Mac
venv\Scripts\activate   # En Windows

Instalar dependencias:

pip install pandas numpy matplotlib seaborn scikit-learn statsmodels

Configurar el archivo CSV:

Asegúrate de que el archivo mi_archivo.csv tenga las siguientes columnas:

quantity: Cantidad de productos vendidos.

price: Precio del producto.

discount: Porcentaje de descuento aplicado.

region: Región de la venta.

date: Fecha de la transacción (si aplica).

Ejecución del Proyecto

Cargar y explorar los datos:

Utiliza el script para cargar y analizar los datos iniciales:

python analisis_eda.py

Entrenar y evaluar modelos:

Ejecuta el script de entrenamiento y evaluación:

python modelado_predictivo.py

Resultados Esperados

Análisis Exploratorio:

Gráficos que muestran las tendencias, estacionalidades y distribuciones de los ingresos diarios.

Identificación de outliers y su impacto.

Modelos Predictivos:

Regresión Lineal Múltiple:

MAE y  moderados que reflejan un ajuste lineal.

Random Forest / Gradient Boosting:

Mejor rendimiento al capturar relaciones no lineales.

Contribuciones

Si deseas contribuir a este proyecto:

Realiza un fork del repositorio.

Crea una rama para tus cambios:

git checkout -b feature/nueva_funcionalidad

Envía un pull request con tus propuestas.

Contacto

Para preguntas o sugerencias, contacta a:

Nombre: Edwin Pulgarin

Correo: edwin.pulgarin@correounivalle.edu.co
