## Financial Parenting Analytics & Behavioural Nudges (Fintech Case Study)

### Project Context
This project was completed as an MSc Business Analytics dissertation in collaboration with **BabyReady Finance**, a UK-based fintech startup focused on helping new and expecting parents plan their finances.

Due to confidentiality constraints, this repository contains **sanitised analysis code, visual outputs, and high-level logic**, rather than the full dissertation document or proprietary datasets.

---

### Business Problem
New parents in the UK face significant financial pressure due to rising childcare costs, uneven cost distribution across life stages, and low savings resilience.

The project sought to answer:
- How much does it realistically cost to raise a child across different life stages?
- At which points do families face the highest financial stress?
- How can data-driven behavioural nudges improve savings behaviour and financial resilience?

---

### Data Sources (Public & Secondary)
- **CPAG – Cost of a Child Report**
- **ONS – Family Spending Survey**
- **Bank of England – NMG Household Survey**

These datasets were used to model lifetime child-rearing costs, childcare expenditure patterns, family-type differences, and household savings vulnerability.

---

### Analytical Approach
- Cleaned and harmonised multi-source national datasets using Python
- Built age-based cost profiles from birth to age 18
- Modelled cumulative and annual child-related costs
- Compared cost burdens across family structures (couple vs lone-parent households)
- Analysed childcare cost spikes and the impact of government support schemes
- Assessed savings vulnerability across households with children
- Designed a rule-based behavioural nudge framework informed by analytical insights

---

### Key Insights
- Raising a child represents a six-figure financial commitment over 18 years
- Childcare costs dominate expenditure in the early years, creating severe cash-flow pressure
- Costs are non-linear, peaking in infancy and again during adolescence
- Lone-parent households face significantly higher lifetime costs due to lack of cost-sharing
- A substantial proportion of households with children have little or no emergency savings
- Government childcare support can reduce costs by up to 60%, yet remains underutilised

---

### Behavioural Nudge Framework
Based on the analysis, a prototype nudge logic was designed to trigger personalised financial prompts based on:
- Child age and life-stage transitions
- Family structure
- Savings adequacy and vulnerability
- Childcare cost spikes
- Eligibility for government support schemes

Example nudges include:
- Encouraging savings accumulation before early childcare years
- Redirecting post-childcare cost reductions into long-term savings
- Prompting enrolment into Tax-Free Childcare and free childcare schemes
- Emergency fund nudges for financially vulnerable households

---

### Business Impact
This project provided BabyReady Finance with:
- A data-backed understanding of financial pressure points in parenthood
- Visual analytics suitable for in-app integration
- A scalable framework for personalised, life-stage-based nudges
- Strategic differentiation from generic budgeting and savings apps

---

### Tools Used
- Python (pandas, matplotlib, seaborn, plotly)
- Jupyter Notebook
- Behavioural economics principles
