# Global Purchasing Power Parity Analysis
## Testing the Law of One Price via the Big Mac Index

---

### 📌 Objective

This project empirically tests the **Law of One Price** using The Economist's Big Mac Index to evaluate currency valuation and purchasing power parity across global markets.

---

### 🔍 Methodology

- Constructed a structured dataset from The Economist's 2015 Big Mac pricing data using Python dictionaries and pandas
- Calculated **implied PPP exchange rates** based on Big Mac prices: `Implied PPP = (Local Price / US Price)`
- Computed **currency misalignment**: `% Valuation = [(Market Rate - Implied PPP) / Implied PPP] × 100`
- Identified over/undervaluation relative to the US Dollar baseline

---

### 📊 Key Findings

*[Insert your specific findings here. Example:]*

- **Norwegian Krone (NOK):** Overvalued by **X%** relative to the US Dollar
- **[Currency Name]:** Undervalued by **Y%**, indicating potential arbitrage opportunities
- **[Currency Name]:** Approximately at parity with PPP predictions

**Economic Interpretation:**  
Deviations from the Law of One Price reflect non-tradable inputs (labor, rent), trade barriers, and local market conditions—demonstrating that while PPP provides a useful benchmark, real-world frictions prevent perfect price convergence.

---

### 💡 Skills Demonstrated

Economic theory application • Data structure design • Exchange rate analytics • Cross-country comparative analysis

---

*Data Source: The Economist's Big Mac Index (2015)*
