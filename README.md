# 📊 Dashboard de Analítica Financiera y Riesgo de Liquidez  
## Caso de Estudio en Data Science – ACUAMAR S.A.

<p align="center">
  <img src="figures/hero_dashboard.png" width="900"/>
</p>

<p align="center">
  <b>Análisis Exploratorio (EDA)</b> · <b>Pronóstico de Series de Tiempo</b> · <b>Simulación de Riesgo</b> · <b>Analítica Financiera</b>
</p>

---

## 🎯 Resumen Ejecutivo

<p align="center">
  <img src="figures/kpis_financieros.png" width="750"/>
</p>

<p align="center">
  <b>Capital de Trabajo Neto:</b> 140,509,329 COP &nbsp;|&nbsp;
  <b>Margen Bruto:</b> 47.48% &nbsp;|&nbsp;
  <b>Días de Cartera:</b> 28
</p>

---

## 🧠 Problema de Negocio

<p align="center">
  <img src="figures/business_context.png" width="850"/>
</p>

**Objetivo:**  
Predecir el flujo de caja y cuantificar el riesgo de liquidez en una empresa industrial B2B, considerando estacionalidad, costos operativos ocultos y obligaciones fiscales.

---

## 📂 Descripción del Dataset

<p align="center">
  <img src="figures/dataset_overview.png" width="800"/>
</p>

| Variable | Descripción |
|--------|-------------|
| FECHA | Índice temporal (mensual) |
| Cobros_Clientes | Entradas de caja |
| Pagos_Proveedores | Salidas de caja |
| Efectivo_Inicial | Liquidez inicial |
| Ventas_Gravadas | Base gravable de IVA |
| Gastos_Gravados | IVA descontable |
| Base_Retencion | Retenciones aplicables |
| Gasto_Nomina | Costos laborales |

---

## 🔍 Análisis Exploratorio de Datos (EDA)

### Dinámica Histórica del Flujo de Caja
<p align="center">
  <img src="figures/cobros_vs_pagos.png" width="850"/>
</p>

*Análisis de descalces históricos entre ingresos y egresos.*

---

### Alertas de Liquidez
<p align="center">
  <img src="figures/alerta_liquidez_flujo_caja.png" width="850"/>
</p>

*Validación del umbral mínimo de liquidez y detección temprana de riesgos.*

---

## 📈 Pronóstico del Flujo de Caja (Prophet)

<p align="center">
  <img src="figures/flujo_caja_proyectado.png" width="850"/>
</p>

*Proyección de entradas y salidas acumuladas a un horizonte de 12 meses.*

---

## 🧾 Pronóstico y Control de Impuestos

<p align="center">
  <img src="figures/control_impuestos.png" width="850"/>
</p>

*Estimación mensual de IVA, retenciones e impuesto de renta para control fiscal.*

---

## 📉 Dashboard de Riesgo Financiero  
### ARIMA + Simulación Monte Carlo

<p align="center">
  <img src="figures/kpis_riesgos.png" width="780"/>
</p>

<p align="center">
  <b>Probabilidad de Fallo de Liquidez:</b> 0.00% &nbsp;|&nbsp;
  <b>Saldo Final Esperado:</b> 1.316 B COP &nbsp;|&nbsp;
  <b>Escenario Pesimista (P10):</b> 1.269 B COP
</p>

---

### Escenarios Monte Carlo
<p align="center">
  <img src="figures/montecarlo_escenarios.png" width="900"/>
</p>

---

### Distribución del Saldo Final
<p align="center">
  <img src="figures/histograma_saldos_finales.png" width="900"/>
</p>

---

## 🧠 Interpretación Ejecutiva

- Flujo de caja proyectado consistentemente positivo  
- Riesgo de liquidez prácticamente nulo en el horizonte analizado  
- Alta resiliencia financiera ante escenarios adversos  
- Metodología robusta y replicable para análisis financiero predictivo  

---

## 🧰 Stack Tecnológico

<p align="center">
  <img src="figures/tech_stack.png" width="650"/>
</p>

- **Python**
- pandas · numpy
- matplotlib · seaborn
- statsmodels
- prophet
- plotly express
- ARIMA
- Streamlit

---



