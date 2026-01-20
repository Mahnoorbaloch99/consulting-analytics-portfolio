## Flight Price Prediction – Predictive Analytics Case Study

### Business Problem
Flight ticket prices are volatile and influenced by multiple operational and market factors.
This project builds a predictive model for flight ticket prices and evaluates the key drivers behind price variation.

A specific business question explored:
**Does departure time significantly impact flight ticket prices?**

---

### Data & Tools
- Dataset: Historical flight pricing data (Kaggle)
- Features: Airline, route, departure time, duration, stops, ticket price
- Tools: Python (Pandas, Scikit-learn, XGBoost, Matplotlib)

---

### Analytical Approach
- Cleaned and validated raw flight pricing data
- Removed price outliers using the IQR method
- Engineered features from date and time variables
- Encoded categorical variables for machine learning
- Trained and tuned multiple models using cross-validation
- Selected the best-performing model based on RMSE

---

### Key Insights
- Flight duration is the strongest predictor of ticket price
- Airline choice significantly impacts pricing, with premium carriers charging higher fares
- Departure time has minimal impact on ticket prices
- Direct flights generally command a price premium

---

### Model Performance
- Best model: Tuned XGBoost
- Lowest RMSE: ~1960
- Tree-based models outperformed linear and neural network models

---

### Business Implications
- Airlines should focus on route length and service positioning rather than departure timing
- Travel platforms can guide users away from misleading time-based price assumptions
- Predictive models can support pricing optimisation and revenue management

---

### Next Steps
- Incorporate real-time pricing and demand data
- Deploy the model via a lightweight web application
