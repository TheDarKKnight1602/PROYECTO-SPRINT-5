# PROYECTO-SPRINT-5]


## 📊 ¿Cuál es la mejor tarifa? - Análisis de Megaline

### 🧠 Propósito del Proyecto

Este análisis fue realizado para la empresa de telecomunicaciones **Megaline**, la cual desea saber **cuál de sus dos tarifas prepago, *Surf* o *Ultimate*, genera más ingresos**. A partir de una muestra de 500 clientes, el objetivo es entender el comportamiento de uso y comparar los ingresos generados por cada plan para orientar decisiones comerciales como la asignación de presupuestos publicitarios.

---

### 📁 Datos utilizados

Se utilizaron cinco conjuntos de datos:

* `megaline_users.csv`: Información general de los usuarios (ID, ciudad, fecha de registro, plan, etc.)
* `megaline_calls.csv`: Registro de llamadas realizadas por los usuarios
* `megaline_messages.csv`: Registro de mensajes enviados
* `megaline_internet.csv`: Datos del tráfico de internet por sesión
* `megaline_plans.csv`: Condiciones de los planes *Surf* y *Ultimate* (límites y costos)

---

### 🔍 Análisis realizado

1. **Carga y limpieza de datos**:

   * Conversión de fechas
   * Agrupación por usuario y mes
   * Enriquecimiento con columnas adicionales como duración del servicio

2. **Agregación mensual por usuario**:

   * Minutos utilizados
   * Mensajes enviados
   * Datos de internet consumidos

3. **Cálculo de ingresos por usuario**:

   * Se compararon los consumos mensuales con los límites del plan y se calcularon los ingresos generados por cada usuario considerando tarifas por excedentes.

4. **Análisis descriptivo**:

   * Medias, varianzas y distribuciones por tipo de plan
   * Gráficos comparativos (barras, histogramas y diagramas de caja)

5. **Pruebas estadísticas**:

   * Se aplicaron pruebas de hipótesis para determinar si las diferencias en ingresos entre planes son estadísticamente significativas.

---

### 💡 Conclusiones preliminares

* Los usuarios del plan **Ultimate** tienden a usar más minutos y datos, pero el plan también es más costoso.
* En promedio, el **plan Surf genera más ingresos por excedentes** cuando los usuarios superan los límites.
* Sin embargo, el análisis completo requiere una evaluación de significancia estadística para validar las diferencias observadas.


