🚧 Border Crossing Data – Traffic Volume Prediction

This project uses machine learning to analyze and predict traffic volumes at U.S. border crossings. By applying Random Forest regression on public data, the goal is to support smarter resource planning and operational efficiency at entry points.

⸻

Objective

To forecast border crossing volumes using geographic and categorical features such as port name, state, date, and measure. The project helps visualize trends and provide actionable insights for traffic management and planning.

⸻

📁 Dataset Overview

Source: U.S. Customs and Border Protection (CBP) public datasets
Features include:
	•	Port Name
	•	State
	•	Border (North/South)
	•	Date
	•	Measure (e.g., Pedestrians, Vehicles, Containers)
	•	Entry Value
	•	Location Coordinates

⸻

🔍 Project Workflow

📊 Data Preprocessing
	•	Cleaned and filtered time series data
	•	Encoded categorical features (e.g., border, measure)
	•	Extracted date components (month, year) for seasonality analysis

🧠 Modeling
	•	Trained a Random Forest Regressor to predict traffic volume (entry count)
	•	Evaluated performance using:
	•	Mean Absolute Error (MAE)
	•	Mean Squared Error (MSE)
	•	R² Score

📈 Visualizations
	•	Time series plots of border traffic trends
	•	Bar charts for port-level traffic volume
	•	Residuals and prediction-vs-actual plots to assess model accuracy

⸻

✅ Results & Insights
	•	The model captured seasonal and regional traffic patterns
	•	High-traffic ports and peak months were clearly identified
	•	Visualizations helped surface bottlenecks and outliers for deeper review

⸻

🧰 Tools & Technologies

Programming:
Python

Libraries:
pandas, numpy, scikit-learn, matplotlib, seaborn

Modeling:
Random Forest Regression

Development Tools:
Jupyter Notebook, Git, GitHub

⸻

💡 Future Work
	•	Try time-series specific models (ARIMA, Prophet)
	•	Add weather or holiday data for better seasonal forecasting
	•	Deploy as a simple dashboard for live volume monitoring

⸻
