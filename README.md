# 📊 Análisis de Tarifas Megaline

## 📌 Descripción del Proyecto
Este proyecto analiza el comportamiento de los clientes de **Megaline**, un operador de telecomunicaciones que ofrece dos planes de prepago: **Surf** y **Ultimate**.  
El objetivo es determinar cuál de los planes genera más ingresos y así orientar decisiones de marketing y presupuesto.

## 🧾 Contexto
La empresa desea identificar qué tarifa aporta mayores ingresos para ajustar su presupuesto publicitario.  
Se dispone de datos de **500 clientes**, incluyendo información sobre llamadas, mensajes y uso de internet durante 2018.

## 🗂️ Diccionario de Datos
El análisis se basa en cinco tablas:
- **users** → información de los clientes (edad, ciudad, plan, fechas de registro y baja).  
- **calls** → duración y fecha de cada llamada.  
- **messages** → cantidad y fecha de los SMS enviados.  
- **internet** → volumen de datos usados por sesión.  
- **plans** → detalles de las tarifas (minutos, SMS, GB incluidos y costos adicionales).

## 🧠 Metodología
1. **Preparación de datos:** limpieza, conversión de tipos y corrección de errores.  
2. **Cálculo de métricas mensuales:** llamadas, SMS, datos y facturación por usuario.  
3. **Análisis descriptivo:** estadísticas, histogramas y distribución de uso por plan.  
4. **Pruebas de hipótesis:** comparación de ingresos promedio entre planes y regiones.

## 🧮 Herramientas Utilizadas
- Python 🐍  
- Librerías: `pandas`, `numpy`, `matplotlib`, `scipy`  
- Jupyter Notebook 💻

## 📈 Resultados Principales
- El plan **Surf** genera mayores ingresos totales debido a los excedentes y su mayor número de usuarios.  
- El plan **Ultimate** muestra ingresos más estables y homogéneos.  
- Las pruebas estadísticas confirman diferencias significativas en los ingresos promedio entre ambos planes.  
- No se encontraron diferencias relevantes entre usuarios de Nueva York–Nueva Jersey y otras regiones.

## ✅ Conclusión General

🔎 Tras el análisis de los datos de Megaline se concluye que:

- 📈 **Surf** es el plan más rentable: los usuarios exceden con frecuencia los límites incluidos, generando ingresos adicionales.  
- 💎 **Ultimate** ofrece mayor estabilidad: aunque su cuota mensual es más alta, los ingresos son más homogéneos y predecibles.  
- 📊 Las pruebas estadísticas confirman diferencias significativas en los ingresos promedio entre ambos planes.  
- 🌍 No se encontraron diferencias relevantes en ingresos entre usuarios de Nueva York–Nueva Jersey y otras regiones.  

✨ **Impacto para Megaline:**  
Los resultados permiten orientar la estrategia de marketing hacia el plan **Surf** para maximizar ingresos, mientras que el plan **Ultimate** puede posicionarse como una opción **premium** para clientes que valoran estabilidad y beneficios amplios.

---

## 📂 Estructura del Repositorio

megaline-tarifas/
│
├── datasets/
│   ├── megaline_calls.csv
│   ├── megaline_internet.csv
│   ├── megaline_messages.csv
│   ├── megaline_plans.csv
│   └── megaline_users.csv
│
├── megaline_analysis.ipynb
└── README.md