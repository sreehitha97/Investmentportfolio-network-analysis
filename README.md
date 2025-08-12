# 📊 Fairholme Capital Investment Network Analysis (Simulated Data, 2019–2023)

## 📌 Overview  
This project uses **generated investment data** resembling quarterly holdings of major “superinvestors” to analyse relationships between their portfolios.  

The focus is on **Fairholme Capital (Bruce Berkowitz)**, studied in the context of other fictional superinvestors, with special attention to changes during the COVID-19 pandemic.  

- **Nodes** = Investors  
- **Edges** = Shared stock holdings (weighted by number of common companies)  
- Dataset is **entirely synthetic**, created for an academic data analysis scenario.

---

## 🎯 Objectives  
- Construct & analyse co-investor networks for each quarter.  
- Compare Fairholme Capital’s ego network to the overall investor network.  
- Identify central “superinvestors” and detect portfolio-based communities.  
- Track changes in network properties over time, highlighting the pandemic period.  
- Discuss diversification, concentration, and possible strategy shifts based on simulated portfolio composition.

---

## 📂 Dataset  
- **Type:** Simulated (artificially generated for coursework)  
- **Period:** Q1 2019 – Q2 2023  
- **Format:** CSV files — first column = investor name, remaining columns = companies in their portfolio.  
- **Network rule:** Edge exists if two investors share ≥ 1 stock; weight = count of shared stocks.

---

## 🛠️ Tools & Methods  
- **Python libraries:** Pandas, NumPy, NetworkX, Matplotlib, Seaborn, python-louvain  
- **Analysis techniques:**  
  - Degree & strength distribution  
  - Clustering coefficient  
  - Assortativity  
  - Louvain community detection  
  - Watts–Strogatz small-world modelling  
  - Temporal trend analysis

---

## 📊 Key Insights (from synthetic data)  
- The whole investor network shows **small-world properties** with high clustering.  
- Simulated Fairholme portfolio expanded in Q2 2020 with more common low-risk stocks.  
- Strong investor “hubs” connect large portions of the network
