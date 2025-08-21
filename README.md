# 
# 🚚 Capacitated Vehicle Routing Problem (CVRP)

Questo progetto affronta il problema del **Capacitated Vehicle Routing (CVRP)** utilizzando tre diversi approcci di risoluzione, confrontandone risultati e prestazioni.

## ⚙️ Approcci Implementati

1. **Approccio esatto con Gurobi (`gurobipy`)**
   - Risoluzione ottimale tramite programmazione lineare intera.
   - Richiede una **licenza Gurobi attiva** (accademica o WLS).

2. **Approccio euristico**
   - Algoritmo **Clarke & Wright Savings** migliorato con **Nearest Neighbor** e **3-opt**.
   - Produce soluzioni rapide, vicine all’ottimo.

3. **Algoritmo genetico (GA)**
   - Approccio metaeuristico evolutivo per ottenere soluzioni approssimate di buona qualità.

## 🛠️ Tecnologie Utilizzate

<table>
  <tr>
    <td align="center">
      <a href="https://www.python.org/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="50" height="50"/><br>
        Python
      </a>
    </td>
    </td>
    <td align="center">
      <a href="https://www.gurobi.com/" target="_blank">
        <img width="50" height="50" alt="logo-final" src="https://github.com/user-attachments/assets/00bf03f5-168e-46b4-819f-c7eb0fa01196" /><br>
        Gurobi
      </a>
    </td>
    <td align="center">
      <a href="https://numpy.org/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original.svg" width="50" height="50"/><br>
        NumPy
      </a>
    </td>
    </td>
    <td align="center">
      <a href="https://matplotlib.org/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/matplotlib/matplotlib-original.svg" width="50" height="50"/><br>
        Matplotlib
      </a>
    </td>
  </tr>
</table>

## 📦 Requisiti

Prima di eseguire il progetto, installare le dipendenze:

```bash
pip install -r requirements.txt
```
**Nota bene**
- L’approccio esatto richiede una **licenza Gurobi** (`gurobi.lic`).
- Le licenze accademiche possono essere richieste tramite [Gurobi Academic](https://www.gurobi.com/academia/academic-program-and-licenses/).

## 📂 Struttura del progetto

Capacitated-Vehicle-Routing-Problem-CVRP/
│
├── test_instances/ # File di input (.vrp) per le istanze del problema e soluzioni (.sol)
├── CVRP.ipynb # Notebook con approccio esatto (Gurobi)
├── Euristica.ipynb # Notebook con Clarke & Wright + miglioramenti
├── Algoritmo_Genetico.ipynb # Notebook con algoritmo genetico
└── requirements.txt # Dipendenze Python necessarie

## 📊 Risultati e Valutazione

I risultati sono confrontati in termini di:

- Costo totale della soluzione
- Tempo computazionale
- Gap rispetto alla soluzione ottima (quando disponibile)

  ## 👥 Contributors

- [@Vincenzo D'Angelo](https://github.com/vincenzodan)
- [@Giorgio Di Costanzo](https://github.com/GiorgioDiCostanzo)
