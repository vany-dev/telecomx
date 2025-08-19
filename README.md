# 📊 Análisis de Evasión de Clientes (Churn) - TelecomX

## Descripción del Proyecto
Este proyecto tiene como objetivo **analizar el comportamiento de los clientes de TelecomX** y **identificar factores que influyen en la evasión (Churn)**.  
La evasión representa a los clientes que cancelan su servicio, lo que afecta directamente los ingresos de la empresa. El análisis permite generar **insights estratégicos para retener clientes y optimizar servicios**.

---

## 🔹 Contenido del Proyecto
El proyecto incluye un **notebook en Python** con los siguientes pasos:

1. **Importación y limpieza de datos**  
   - Traducción de columnas al español.  
   - Conversión de la variable `abandono` a 0 (No) y 1 (Sí).  
   - Corrección de valores inconsistentes, por ejemplo `'0'` → `"Sin servicio"` en `servicio_internet`.  

2. **Análisis Exploratorio de Datos (EDA)**  
   - Distribución general de la evasión de clientes.  
   - Recuento y visualización de evasión por **variables categóricas** (`genero`, `contrato`, `metodo_pago`, `servicio_internet`, etc.).  
   - Recuento y visualización de evasión por **variables numéricas** (`antiguedad_meses`, `cargo_mensual`, `cargo_total`, etc.).  

3. **Visualizaciones**  
   - Gráficos de barras y pastel para la distribución de la evasión.  
   - Barras apiladas para comparaciones entre categorías.  
   - Barras de medias para variables numéricas según evasión.  

---

## 🔹 Tecnologías Utilizadas
- Python 3.x  
- Pandas  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## 🔹 Principales Hallazgos
- La mayoría de los clientes permanecen en el servicio, pero un **porcentaje importante abandona**, especialmente aquellos con contratos más cortos y ciertos tipos de servicios (Fiber optic).  
- La **antigüedad del cliente y el tipo de contrato** son factores determinantes en la evasión.  
- Algunos métodos de pago y servicios adicionales muestran correlación con abandono, lo que permite orientar estrategias de retención.  

---

## 🔹 Recomendaciones Estratégicas
1. Ofrecer **beneficios o incentivos** a clientes con contratos cortos para reducir abandono temprano.  
2. Mejorar la **calidad de servicios de internet** que presentan más abandono.  
3. Implementar **programas de fidelización** para clientes con alto cargo mensual o total.  
4. Monitorear periódicamente la evasión según **perfil de cliente** y ajustar campañas de retención.  

---

## 🔹 Cómo Ejecutar
1. Abrir el notebook en **Google Colab**.  
2. Ejecutar todas las celdas en orden.  
3. Explorar las visualizaciones y tablas generadas para entender los patrones de evasión.  

---

## 🔹 Autor
**Jhovan Hernández Ramírez**  
Proyecto realizado como parte del Bootcamp de Data Science.

