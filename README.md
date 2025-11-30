# 🐍 python_cartera_inversion_gino  
**Simulación cuantitativa de una cartera global con horizonte de 16 años.**  
Análisis de riesgo, diversificación, factores y proyecciones de largo plazo aplicadas a una cartera diseñada para un niño.

---

## 🎯 Objetivo del proyecto
Este proyecto modela una cartera destinada a mi **sobrino/ahijado de 2 años**, con el objetivo de acompañar el crecimiento de su capital hasta sus **18 años**.  
Se construye una estrategia global, diversificada y eficiente utilizando métodos cuantitativos modernos.

---

## 🧱 Estructura del análisis

### 📊 Parte 1 – Selección y descarga de datos
- Series históricas 2022–2025 descargadas con `yfinance`.  
- Acciones de EE. UU., Latinoamérica, Europa, emergentes, oro y cripto.  
- Limpieza, retornos, volatilidad y matriz de correlación.

### 🔍 Parte 2 – Métricas de riesgo y performance
- Betas y exposición al mercado (CAPM).  
- Ratios de **Sharpe**, **Sortino**, volatilidad anualizada.  
- Regresiones **Fama–French (3 factores)** para entender drivers del rendimiento.  
- Identificación de activos con alpha positivo.

### ⚙️ Parte 3 – Simulación de portafolios
- **10.000 portafolios aleatorios** (Monte Carlo).  
- Selección del portafolio de **Máximo Sharpe**.  
- Visualización interactiva de la **frontera eficiente**.

### 📈 Parte 4 – Evaluación histórica vs SPY
- Retorno base 100 comparado entre portafolio y benchmark.  
- Análisis de drawdowns, caídas y tiempos de recuperación.

### 🧮 Parte 5 – Proyección a 16 años
- Simulación por **Geometric Brownian Motion (GBM)**.  
- Escenarios conservador – esperado – optimista.  
- Amplificación del interés compuesto a largo plazo.

---

## ⭐ Resultados principales

### 1. Performance histórico (2022–2025)
- **Portafolio Óptimo:** +128%  
- **SPY:** +50.8%  
- **Sharpe:** 0.91 (vs 0.34 del SPY)

> El portafolio triplica el rendimiento ajustado por riesgo del SPY.

---

### 2. Riesgo y drawdowns
- Máx. drawdown del portafolio: **–29.6%**  
- Máx. drawdown del SPY: **–24.5%**  
- Recuperación portafolio: **421 días**  
- Recuperación SPY: **707 días**

> Cae un poco más, pero se recupera mucho antes: señal de resiliencia.

---

### 3. Composición óptima (intuición del modelo)
- Peso relevante en **tecnología megacap** (NVDA, MSFT, GOOGL).  
- Diversificación real con **oro, emergentes y Europa**.  
- Participación acotada pero valiosa en **Argentina** (YPF, VIST, PAM, MELI).  
- **BTC** como activo satélite de crecimiento.

> La mezcla maximiza eficiencia, balance y potencial de largo plazo.

---

### 4. Factores Fama–French
- Exposición al factor **crecimiento** (HML negativo).  
- **Alphas positivos** en activos clave: NVDA, BTC, PAM, VIST, YPF.  
- Acciones grandes de EE. UU. explicadas fuertemente por factores (alto R²).  
- Oro, cripto y Argentina = comportamiento más idiosincrático.

---

### 5. Proyección a 16 años
Simulación GBM con 3 escenarios:
- En los **tres**, el portafolio supera al SPY.  
- A 16 años, pequeñas diferencias en rendimiento anual generan enormes brechas de capital.

> No predice el futuro, pero da un marco robusto para visualizar crecimiento potencial.

---

## 🧠 Conclusión final
La cartera diseñada para Gino presenta:
- rendimiento histórico muy sólido  
- riesgo controlado  
- rápida recuperación  
- diversificación global  
- fundamentos cuantitativos modernos  

Es una estrategia pensada para el **largo plazo**, más eficiente que simplemente replicar al SPY y adecuada para un horizonte de 16 años.
