# 📊 TelecomX - Análisis de Churn de Clientes

Este proyecto corresponde al **Desafío #2 de Data Science de Alura Latam**, cuyo objetivo es analizar una base de datos de una empresa ficticia de telecomunicaciones llamada **TelecomX** para identificar los factores asociados a la **cancelación de clientes (Churn)**.

El análisis busca responder preguntas clave como:

- ¿Qué características tienen los clientes que cancelan el servicio?
- ¿Existen servicios o métodos de pago asociados a una mayor tasa de abandono?
- ¿Cómo influyen variables como el precio, la antigüedad o los servicios contratados?

---

# 🎯 Objetivo del proyecto

El objetivo principal es realizar un **análisis exploratorio de datos (EDA)** para identificar patrones y factores que influyen en la cancelación de clientes, permitiendo generar **insights que ayuden a mejorar la retención**.

---

# 🗂️ Dataset

El dataset contiene información de **más de 7000 clientes**, incluyendo variables como:

- Información demográfica
- Servicios contratados
- Tipo de contrato
- Método de pago
- Cargos mensuales y totales
- Antigüedad del cliente
- Estado de cancelación (Churn)

La variable principal analizada fue:
# 📊 TelecomX - Análisis de Churn de Clientes

Este proyecto corresponde al **Desafío #2 de Data Science de Alura Latam**, cuyo objetivo es analizar una base de datos de una empresa ficticia de telecomunicaciones llamada **TelecomX** para identificar los factores asociados a la **cancelación de clientes (Churn)**.

El análisis busca responder preguntas clave como:

- ¿Qué características tienen los clientes que cancelan el servicio?
- ¿Existen servicios o métodos de pago asociados a una mayor tasa de abandono?
- ¿Cómo influyen variables como el precio, la antigüedad o los servicios contratados?

---

# 🎯 Objetivo del proyecto

El objetivo principal es realizar un **análisis exploratorio de datos (EDA)** para identificar patrones y factores que influyen en la cancelación de clientes, permitiendo generar **insights que ayuden a mejorar la retención**.

---

# 🗂️ Dataset

El dataset contiene información de **más de 7000 clientes**, incluyendo variables como:

- Información demográfica
- Servicios contratados
- Tipo de contrato
- Método de pago
- Cargos mensuales y totales
- Antigüedad del cliente
- Estado de cancelación (Churn)

La variable principal analizada fue:
# 📊 TelecomX - Análisis de Churn de Clientes

Este proyecto corresponde al **Desafío #2 de Data Science de Alura Latam**, cuyo objetivo es analizar una base de datos de una empresa ficticia de telecomunicaciones llamada **TelecomX** para identificar los factores asociados a la **cancelación de clientes (Churn)**.

El análisis busca responder preguntas clave como:

- ¿Qué características tienen los clientes que cancelan el servicio?
- ¿Existen servicios o métodos de pago asociados a una mayor tasa de abandono?
- ¿Cómo influyen variables como el precio, la antigüedad o los servicios contratados?

---

# 🎯 Objetivo del proyecto

El objetivo principal es realizar un **análisis exploratorio de datos (EDA)** para identificar patrones y factores que influyen en la cancelación de clientes, permitiendo generar **insights que ayuden a mejorar la retención**.

---

# 🗂️ Dataset

El dataset contiene información de **más de 7000 clientes**, incluyendo variables como:

- Información demográfica
- Servicios contratados
- Tipo de contrato
- Método de pago
- Cargos mensuales y totales
- Antigüedad del cliente
- Estado de cancelación (Churn)

La variable principal analizada fue:
Churn o cancelacion despues del cambio de nombre(0 = cliente activo, 1 = cliente que canceló)

# 🧹 Limpieza y preparación de datos

Durante el proceso de preparación se realizaron varias transformaciones:

- Normalización de **estructuras JSON anidadas** presentes en el dataset.
- Eliminación de **filas con valores inválidos o faltantes**.
- Conversión de tipos de datos a sus formatos correctos.
- Transformación de variables binarias **Sí/No → 1/0** para facilitar análisis y visualización.
- Renombrado de columnas para mejorar la legibilidad.
- Creación de algunas variables derivadas (como cargos diarios).

Estas transformaciones permitieron obtener un dataset limpio y listo para análisis.

---

# 📈 Análisis exploratorio

Se realizaron múltiples visualizaciones utilizando:

- **Pandas**
- **Matplotlib**
- **Seaborn**

Entre los análisis principales se estudiaron:

### Métodos de pago
Se evaluó la relación entre los métodos de pago y la tasa de cancelación.

### Antigüedad del cliente
Se analizó cómo cambia la tasa de churn según los meses que el cliente lleva con el servicio.

### Cargos mensuales
Se identificaron rangos de precios con mayor riesgo de cancelación.

### Servicios contratados
Se evaluó el impacto de servicios adicionales como:

- soporte técnico  
- seguridad online  
- respaldo online  
- protección de dispositivos  
- streaming

### Segmento de adultos mayores
Se investigó el comportamiento de cancelación en clientes mayores y su relación con el soporte técnico.

---

# 🔎 Principales hallazgos

Entre los insights más relevantes del análisis se encontraron:

- El **método de pago Electronic Check** presenta una tasa de cancelación significativamente mayor que otros métodos.
- El servicio de **internet por fibra óptica** muestra una tasa de abandono considerablemente superior al servicio DSL.
- Los clientes **sin soporte técnico** presentan una probabilidad mucho mayor de cancelar el servicio.
- En el segmento de **adultos mayores**, la ausencia de soporte técnico está fuertemente asociada con la cancelación.
- La mayor parte de las cancelaciones ocurre durante los **primeros meses de servicio**.
- Existe una relación entre **mayores cargos mensuales y mayor tasa de cancelación**.

---

# 💡 Posibles líneas de acción

A partir del análisis se identificaron algunas áreas que podrían investigarse más a fondo:

- Evaluar posibles problemas asociados al **Electronic Check**.
- Analizar las causas de la alta cancelación en **clientes con fibra óptica**.
- Considerar la importancia del **soporte técnico** como factor de retención.
- Diseñar estrategias para mejorar la **retención durante los primeros meses** del cliente.

---

# 🛠️ Tecnologías utilizadas

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter / Google Colab

---

# 📌 Autor Edwardo Gautier

Proyecto realizado como parte del **Desafío TelecomX - Data Science** de Alura Latam.
