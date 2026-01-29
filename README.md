# loan_default_survival_analysis
PROYECTO 1 — ANÁLISIS DE SUPERVIVENCIA DE DEFAULT DE PRÉSTAMOS


# Análisis de Supervivencia de Default en Préstamos

## 1. Problema de Negocio
La pregunta clave para un banco o fintech es: 
**¿Cuál es la probabilidad de que un cliente haga default en un préstamo antes de su término?**  
Esto permite optimizar decisiones de crédito, mitigar riesgos y ajustar tasas de interés.

## 2. Dataset
- Fuente: Lending Club Loan Data (Kaggle)
- Contiene información sobre préstamos, pagos, estado del préstamo, ingresos y perfil crediticio.

## 3. Variables Clave
- **Tiempo**: meses desde otorgamiento hasta cierre o default  
- **Evento**: 1 si default (`Charged Off`), 0 si pagado/activo  
- **Predictoras**: monto préstamo, tasa interés, ingresos, antigüedad laboral, calificación crediticia, tipo de vivienda, propósito del préstamo, ratio deuda/ingreso, utilización de crédito revolvente

## 4. Modelos Aplicados
1. Kaplan–Meier → estimación de supervivencia global  
2. Cox Proportional Hazards → impacto de variables en riesgo de default  
3. Random Survival Forest → predicción flexible y no lineal

## 5. Resultados
- Curvas de supervivencia para diferentes grupos (p. ej., grado de crédito)  
- Identificación de variables más influyentes  
- Predicción individual de riesgo de default

## 6. Conclusión Ejecutiva
Este análisis permite:
- Identificar clientes de alto riesgo antes de otorgar préstamos  
- Ajustar políticas de crédito y tasas de interés  
- Tomar decisiones basadas en datos reales


