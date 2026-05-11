# Eficiencias de detectores no LHCb para ións lixeiros (Run 3)

Este repositorio contén o código e a análise desenvolvida para o meu **Traballo de Fin de Grao (TFG)**. O obxectivo principal é o cálculo das eficiencias de reconstrución e identificación de muóns no experimento **LHCb** durante o **Run 3**.

##  Descrición do Proxecto
A análise céntrase no estudo de sistemas de colisión de ións lixeiros:
* **pO** (Protón-Osíxeno)
* **OO** (Osíxeno-Osíxeno)
* **NeNe** (Neón-Neón)

Utilízase a técnica de **Tag-and-Probe** empregando a resonancia $J/\psi \to \mu^+\mu^-$ para extraer as eficiencias directamente dos datos de colisión e simulación (MC).

## 🛠️ Tecnoloxías utilizadas
* **Linguaxe:** Python (PyROOT)
* **Framework de análise:** [ROOT](https://root.cern/) e **RooFit**
* **Entorno:** VS Code vía SSH no servidor do LHCb / Instituto

##  Estrutura do Repositorio
* `/notebooks`: Ficheiros `.ipynb` cos cortes para filtrar, axustes de masa e extracción de rendementos.


## 📊 Metodoloxía
1. **Selección de eventos:** Filtrado de candidatos $J/\psi$ con cortes de calidade.
2. **Axuste de Masa Invariante:** Modelado do sinal (Crystal Ball/Gaussiana) e do fondo ( Exponencial) usando **RooFit**.
3. **Eficiencias:** Cálculo de eficiencias en bins de $p_T$ e $\eta$.
4. **Sistemáticos:** Estimación de incertezas asociadas ao modelo de axuste.

---
*Autor: [Roi Casal Blanco]* *Institución: [IGFAE]* *Ano: 2026*
