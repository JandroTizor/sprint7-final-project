# 📊 Proyecto 6: Análisis de una Empresa de Telecomunicaciones (ConnectaTel)

## 🎯 Objetivo del proyecto

El objetivo de este proyecto es analizar el comportamiento de uso de los clientes de ConnectaTel (llamadas y mensajes), con el fin de identificar patrones, detectar valores atípicos y segmentar a los usuarios según su nivel de uso y características demográficas.

A partir de este análisis, se busca generar insights accionables que permitan optimizar la oferta de planes, mejorar la experiencia del cliente y apoyar la toma de decisiones del negocio.

---

## 🗂️ Datasets utilizados

Se trabajó con tres fuentes principales de datos:

* **plans.csv**
  Contiene información sobre los planes disponibles (precio, minutos, datos y costos adicionales).

* **users_latam.csv**
  Incluye datos de los usuarios: edad, ciudad, fecha de registro, tipo de plan y churn.

* **usage.csv**
  Registra la actividad de los usuarios: llamadas (duración) y mensajes (longitud).

---

## ⚙️ Etapas del análisis

El proyecto se desarrolló siguiendo un flujo estructurado:

1. **Carga y exploración de datos**
   Revisión inicial de estructura, tipos de datos y primeras observaciones.

2. **Identificación de problemas de calidad**
   Detección de valores nulos, sentinels y fechas inconsistentes.

3. **Limpieza de datos**
   Corrección de valores inválidos, estandarización de fechas y tratamiento de nulos.

4. **Construcción de variables (feature engineering)**
   Creación de métricas por usuario (mensajes, llamadas, minutos).

5. **Análisis exploratorio (EDA)**
   Estadísticas descriptivas, distribuciones y visualización de variables clave.

6. **Detección de outliers**
   Identificación de usuarios con comportamiento extremo mediante boxplots e IQR.

7. **Segmentación de clientes**
   Clasificación por nivel de uso (bajo, medio, alto) y grupo de edad.

8. **Generación de insights**
   Interpretación de resultados y propuestas de valor para el negocio.

---

## ▶️ Cómo ejecutar el notebook

Puedes ejecutar este proyecto fácilmente en **Google Colab**:

1. Abre Google Colab: https://colab.research.google.com/
2. Sube el archivo `.ipynb` del proyecto
3. Sube los datasets (`plans.csv`, `users_latam.csv`, `usage.csv`) en la sección de archivos
4. Ejecuta las celdas en orden

También puedes ejecutarlo localmente si tienes Python instalado con Jupyter Notebook.

---

## 🔁 Guía de reproducción

Para reproducir este análisis:

1. Clona o descarga este repositorio
2. Asegúrate de tener instaladas las siguientes librerías:

   * pandas
   * numpy
   * seaborn
   * matplotlib
3. Coloca los datasets en la ruta `/datasets/` o ajusta las rutas en el código
4. Ejecuta el notebook paso a paso
5. Verifica que los resultados coincidan con los análisis documentados

---

## 💡 Resultado final

El análisis permitió identificar:

* Segmentos de usuarios según su nivel de uso
* Predominio de usuarios adultos con uso medio
* Presencia de usuarios intensivos (heavy users)
* Oportunidades claras de upselling y activación

Estos hallazgos pueden utilizarse para mejorar la estrategia comercial, optimizar los planes y aumentar la retención de clientes.

---

## 🚀 Autor

Proyecto desarrollado como parte de formación en análisis de datos.
