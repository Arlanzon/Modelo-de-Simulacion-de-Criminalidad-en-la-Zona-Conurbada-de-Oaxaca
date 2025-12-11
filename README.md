# Simulación de la incidencia delictiva en municipios conurbados de Oaxaca

Este repositorio contiene un modelo de simulación basado en agentes (ABM) desarrollado en **AnyLogic** para analizar la incidencia delictiva en 27 municipios conurbados de la Zona Metropolitana de Oaxaca (ZMO), México.  
El modelo utiliza datos históricos del **Secretariado Ejecutivo del Sistema Nacional de Seguridad Pública (SESNSP)** y población del **INEGI** para generar eventos delictivos mediante procesos Poisson.

## Objetivo del proyecto

Explorar, de forma simulada, **dónde** y **cuándo** es más probable que ocurran delitos en la ZMO, enfocándose en tres subtipos:

- Homicidio doloso  
- Lesiones dolosas  
- Violencia familiar  

El modelo permite:

- Representar cada municipio como un agente autónomo con:
  - Población
  - Conectividad (vecindad geográfica)
  - Tasas delictivas por 100 000 habitantes
- Generar delitos mensuales usando distribuciones de Poisson
- Analizar distribución espacial y temporal de los delitos
- Probar escenarios hipotéticos de incremento o reducción en las tasas delictivas
