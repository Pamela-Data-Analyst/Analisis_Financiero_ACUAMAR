# 📊 Análisis Financiero Predictivo y Simulación de Riesgo de Liquidez

<p align="center">
  <img src="figures/hero_dashboard.png"/>
</p>

Proyecto de **Data Science aplicado a finanzas corporativas**, enfocado en la **proyección de flujo de caja** y la **evaluación del riesgo de liquidez** mediante modelos de series de tiempo y simulación Monte Carlo.

---

## 🏢 Contexto del Negocio

<p align="center">
  <img src="figures/business_context.png"/>
</p>

El proyecto analiza el comportamiento financiero de una empresa industrial B2B, caracterizada por:
- Ciclos de cobro largos
- Altos costos operativos
- Carga fiscal relevante
- Riesgo de descalce de liquidez

El objetivo es **anticipar escenarios financieros adversos** y apoyar la toma de decisiones basada en datos.

---

## 🗂️ Dataset Overview

<p align="center">
  <img src="figures/dataset_overview.png"/>
</p>

El dataset está estructurado como una **serie de tiempo financiera mensual**, organizada en:

- **Ingresos**: cobros a clientes, ventas gravadas  
- **Egresos**: pagos a proveedores, nómina  
- **Impuestos**: IVA y retenciones  
- **Liquidez**: efectivo inicial y saldo de caja  
- **Variable temporal**: fecha (índice mensual)

El diseño del dataset permite análisis exploratorio, modelado temporal y simulación de riesgo.

---

## ⚙️ Stack Tecnológico

<p align="center">
  <img src="figures/tech_stack.png"/>
</p>

El análisis se desarrolla siguiendo un **pipeline de Data Science end-to-end**:

- **Ingesta de Datos**: Excel, CSV  
- **Procesamiento**: Pandas, NumPy  
- **Análisis Exploratorio (EDA)**: Matplotlib, Seaborn  
- **Modelado**: ARIMA, Prophet  
- **Simulación**: Monte Carlo  
- **Visualización y Reportes**: Dashboards, GitHub  

**Lenguaje y entorno**: Python · Jupyter Notebook · Git

---

## 📈 Modelado Predictivo

Se aplican modelos de **series de tiempo** para proyectar el flujo de caja:

- **ARIMA**: captura patrones autoregresivos y estacionales
- **Prophet**: modela tendencia, estacionalidad y efectos de calendario

Los modelos permiten estimar el comportamiento esperado del saldo de caja a futuro.

---

## 📉 Predicción de Riesgo Financiero  
### ARIMA + Simulación Monte Carlo

#### 📌 KPIs de Riesgo

<p align="center">
  <img src="figures/kpis_riesgos.png" width="600"/>
</p>

| Métrica | Valor |
|------|------|
| Probabilidad de fallo de liquidez | 0.00% |
| Saldo final esperado | 1.31 B COP |
| Escenario pesimista (P10) | 1.27 B COP |

> Valores redondeados para visualización.

---

## 🧠 Principales Insights

- La empresa mantiene un **colchón de liquidez sólido** bajo los escenarios simulados.
- El riesgo de liquidez es bajo en el horizonte analizado.
- Los impuestos y costos operativos tienen un impacto directo en la variabilidad del flujo de caja.
- La simulación Monte Carlo permite cuantificar escenarios extremos más allá del valor esperado.

---

## 🚀 Valor del Proyecto

Este proyecto demuestra:
- Aplicación práctica de **Data Science en finanzas**
- Dominio de **series de tiempo y simulación de riesgo**
- Capacidad de **conectar análisis técnico con contexto de negocio**
- Buenas prácticas de **documentación y comunicación de resultados**

---

## 📁 Estructura del Repositorio

