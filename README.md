# 🏭 Análisis de datos operativos para optimización de recursos

## 🧩 Introducción
La optimización de recursos es fundamental para que cualquier empresa reduzca costos operativos y elimine ineficiencias.

En este proyecto se analizaron datos relacionados con:

- La calidad del soluble generado después del maquinado  
- La cantidad de soluble enviada a disposición  
- Registros de mantenimiento predictivo y correctivo por máquina  

El objetivo fue identificar posibles fugas y oportunidades de mejora.

A partir de este análisis, se implementaron estrategias que redujeron la cantidad de soluble dispuesto, disminuyendo gastos operativos y contribuyendo a prácticas más sostenibles.

---

## 🛠️ Tecnologías utilizadas

**EXCEL | POWER BI | RECOLECCIÓN DE DATOS | LIMPIEZA DE DATOS | TRANSFORMACIÓN DE DATOS | EDA | VISUALIZACIÓN**

---

## 🎯 Preguntas clave

- ¿Qué parámetros de calidad del soluble determinan si puede ser reciclado?  
- ¿Qué proporción del soluble se envía a disposición sin tratamiento previo?  
- ¿Qué prácticas actuales generan desperdicio innecesario?  
- ¿Cuál sería el ahorro estimado al recuperar parte del soluble mediante filtración o reciclaje?  

---

## 🔄 Metodología

### 📥 1. Recolección de datos
- Datos obtenidos de formatos físicos en planta  
- Información sobre:
  - Calidad del soluble  
  - Mantenimientos  
  - Manifiestos de disposición  

---

### 🧹 2. Preprocesamiento
- Limpieza de datos  
- Estandarización  
- Eliminación de inconsistencias  
- Verificación de duplicados  

---

### 🤖 3. Modelado predictivo
- Estimación del ahorro potencial mediante:
  - Simulación  
  - Modelos de regresión  
- Variables consideradas:
  - Costo de aceite nuevo  
  - Costo de disposición  
  - Volumen recuperable  

---

### 🔍 4. Clustering
- Clasificación del soluble según nivel de contaminación  
- Identificación de su potencial de recuperación  

---

## 📊 Análisis visual de datos operativos

Este conjunto de visualizaciones permitió:

- Comprender el comportamiento del soluble en el proceso de maquinado  
- Identificar factores críticos de contaminación  
- Evaluar el impacto del mantenimiento en la disposición final del recurso  

---

### 📈 1. Parámetros promedio de calidad por sección
El gráfico de líneas muestra los valores promedio de:

- Concentración (%)  
- pH del soluble  

🔎 Hallazgo: Secciones como la **1 y la 6** presentan desviaciones importantes, indicando deterioro acelerado.

---

### 📊 2. Volumen de disposición por máquina
El gráfico de barras muestra diferencias significativas en el volumen de soluble enviado a disposición.

🔎 Hallazgo: Permite identificar máquinas con mayor desperdicio y posibles causas como:
- Fugas  
- Contaminación  
- Ineficiencias operativas  

---

### 🧪 3. Tipos de contaminación del soluble
El gráfico de dona clasifica los principales contaminantes:

- Basura  
- Residuos de desengrasante  
- Aceites atrapados (*tramp oil*)  
- Viruta metálica  

🔎 Hallazgo: Esta segmentación permitió definir estrategias específicas de recuperación.

---

### 🔧 4. Distribución de mantenimiento
El gráfico circular muestra la proporción entre:

- Mantenimiento predictivo  
- Mantenimiento correctivo  

🔎 Hallazgo: Una mayor proporción de mantenimiento predictivo respalda su impacto positivo en la operación.

---

## 💡 Conclusiones y recomendaciones

### ⚠️ Factores críticos de contaminación
Las desviaciones en la calidad del soluble están directamente relacionadas con prácticas operativas del personal, como:

- Presencia de basura  
- Residuos de desengrasante  
- Materiales ajenos al proceso  

Estos factores aceleran la degradación del soluble.

---

### 🚨 Impacto de las fugas
El análisis de mantenimiento evidenció:

- Máquinas con historial de fugas presentan:
  - Mayor consumo de soluble  
  - Mayor volumen de disposición  
  - Alta variabilidad en la concentración  

---

### ♻️ Oportunidad de recuperación
Una parte significativa del soluble puede recuperarse mediante:

- Filtración  
- Separación de aceites  
- Mejores prácticas de mantenimiento  

Esto representa una oportunidad directa de ahorro.

---

### 🛠️ Relación mantenimiento–estabilidad
Las máquinas con mantenimiento predictivo constante mostraron:

- Mayor estabilidad en la calidad del soluble  
- Menor volumen de disposición  

✅ Confirmando su impacto positivo en eficiencia operativa.

---

## ✅ Recomendaciones

- Estandarizar prácticas de limpieza  
  - Capacitación y concientización del personal  

- Implementar un programa de reciclaje del soluble  
  - Separadores de *tramp oil*  
  - Filtración fina  
  - Centrífugas  

- Priorizar mantenimiento predictivo  
  - En máquinas con historial de fugas  

- Monitorear KPIs clave:
  - Concentración  
  - pH  
  - Conductividad  
  - % de *tramp oil*  
  - Volumen dispuesto por máquina  
  - Frecuencia de fugas  

---

## 🚀 Resultado esperado

Al implementar estas estrategias se logra:

- Reducción de costos operativos  
- Disminución del volumen de residuos  
- Mejora en la eficiencia del proceso  
- Mayor sostenibilidad en la operación  
- Toma de decisiones basada en datos  

<p align="center">
  <img src="Dashboard_soluble.jpg" width="700">
</p>
