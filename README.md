# The Truth About Tech Inflation  
*UIUC Data Dive Project*  

## 📌 Overview  
This project investigates how global semiconductor supply chain stress impacts the inflation of tech products.  
Although consumer-facing metrics like CPI suggest prices are falling, our analysis finds that tech companies continue raising prices — driving hidden inflation across the sector.

## 🧠 Hypothesis  
- Most tech products rely on semiconductors  
- Semiconductor imports strongly influence manufacturing costs  
- Rising semiconductor prices → rising tech product prices  
- Global supply chain disruptions can help predict inflation

## 📊 Data Sources  
We used three major economic indicators:

- **GSCPI (Global Supply Chain Pressure Index):** measures global supply chain stress  
- **PPI for Semiconductors:** producer prices for semiconductor manufacturing  
- **CPI for Tech Goods:** consumer prices (computers, peripherals, smart devices)

## 🛠️ Methodology  
### 1. **KMeans Clustering**  
Used to segment the data into economic “eras” based on patterns in supply chain stress and pricing.

### 2. **XGBoost Regressor Models**  
Trained separately for each cluster to predict future semiconductor price inflation.

### 3. **Rolling Cross-Validation**  
Simulates real-time forecasting by using sliding windows of historical data.

### 4. **Bias Correction**  
Reduces prediction error by adjusting outputs using average cluster-specific bias.

## 🔍 Key Findings  
- **CPI shows a slight downward trend**, giving consumers the illusion of stable tech prices.  
- **Actual inflation is rising steadily**, especially upstream in semiconductor production.  
- **Tech giants accelerate inflation** by increasing product prices faster than CPI reflects.  
- Supply chain stress acts as an early warning signal for tech sector inflation.

## 🌍 Implications  
### **Technology**  
- AI and automation may reduce consumer spending and improve efficiency  
- Hardware reliance increases price sensitivity to semiconductor shortages  

### **Social & Legal**  
- Higher tech prices squeeze consumer budgets  
- Antitrust regulations may limit price manipulation by major tech companies  
- Sustainability constraints will impact manufacturing and inflation

## Other Collaborators
Saumitra G.  
Liam P.  
Jai S.  

## 📬 Contact  
For questions reach out to bobdetanish@gmail.com!
