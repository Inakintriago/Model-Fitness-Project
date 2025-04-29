# 💪 Model Fitness: Estrategia de Retención de Clientes

## 📊 Descripción del Proyecto

Model Fitness es una cadena de gimnasios que busca mejorar su estrategia de retención de clientes mediante el uso de análisis de datos. Uno de los mayores retos para los gimnasios es la **pérdida de clientes**. Este proyecto tiene como objetivo predecir la probabilidad de cancelación de los usuarios, identificar patrones y sugerir medidas para aumentar la lealtad de los clientes.

## 🛠️ Herramientas Utilizadas

- **Python**: Análisis de datos y modelado predictivo.
- **Pandas** y **NumPy**: Limpieza y manipulación de datos.
- **Scikit-learn**: Modelado de clasificación y clustering.
- **Matplotlib** y **Seaborn**: Visualización de patrones de comportamiento.
- **SciPy**: Análisis estadístico.
- **Jupyter Notebook**: Documentación de todo el flujo de trabajo.

## 🔄 Flujo de Trabajo

### 🔍 1. Exploración de Datos

- **Datos ausentes**: Identificación y gestión de valores nulos en las columnas.
- **Análisis descriptivo**: Cálculo de estadísticas clave como promedios, desviación estándar y análisis de grupos por cancelación.
- **Visualización**: Realización de histogramas y gráficos de barras para comparar las características de los clientes que cancelaron con los que permanecieron.
- **Matriz de correlación**: Identificación de relaciones entre las variables y su impacto en la cancelación.

### 🤖 2. Modelado Predictivo

- **Modelos entrenados**: Implementación de dos modelos de clasificación para predecir la probabilidad de cancelación:
  - **Regresión logística**: Para modelar la probabilidad de que un cliente cancele.
  - **Bosque aleatorio**: Para captar interacciones complejas entre variables.
- **Evaluación de modelos**: Comparación de la exactitud, precisión y recall para determinar cuál modelo predice mejor la cancelación de clientes.

### 🧑‍🤝‍🧑 3. Segmentación de Clientes

- **Clustering**: Uso del algoritmo K-means para segmentar a los usuarios en clústeres según sus características.
- **Análisis de clústeres**: Observación de la tasa de cancelación y características clave en cada grupo.
- **Dendrograma**: Análisis visual para determinar el número de clústeres óptimos.

## 📈 Conclusiones y Recomendaciones

### 🚨 1. Grupos con Alta Tasa de Cancelación

- Los clústeres 0, 3 y 4 presentan tasas de cancelación significativamente altas.
- **Recomendación**: Aplicar campañas de fidelización específicas, como descuentos o acceso a clases exclusivas, para reducir la rotación en estos grupos.

### 🏋️‍♀️ 2. Participación en Actividades Grupales

- Los usuarios que participan en clases grupales tienen menos probabilidad de cancelar su membresía.
- **Recomendación**: Incentivar la participación en clases grupales mediante programas de recompensas y descuentos para aquellos que asistan regularmente.

### 🚶‍♀️ 3. Frecuencia de Visitas

- La baja frecuencia de visitas es un indicio clave de cancelación inminente.
- **Recomendación**: Implementar alertas de baja actividad para contactar a los clientes que no han visitado el gimnasio en más de una semana, ofreciendo promociones para reactivar su asistencia.

### ❤️ 4. Clientes Leales

- Los usuarios con más tiempo de membresía tienden a cancelar menos, pero aún pueden beneficiarse de atención personalizada.
- **Recomendación**: Desarrollar un programa de recompensas para los usuarios más leales, con beneficios como masajes o clases exclusivas.

## 🎯 Conclusión General

A través de la segmentación de clientes y el análisis de los factores que influyen en la cancelación, Model Fitness puede optimizar su estrategia de retención. Implementando medidas personalizadas basadas en datos, el gimnasio puede reducir significativamente su tasa de cancelación y mejorar la satisfacción general de sus usuarios.
