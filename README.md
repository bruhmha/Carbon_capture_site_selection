Carbon Capture and Utilization: Optimal Site Selection Using Machine Learning
This repository contains the code and data analysis related to my master's thesis: "Carbon Capture and Utilization: Selecting the Best Carbon Capture Site and Utilization Using Machine Learning". The project focuses on using unsupervised machine learning to identify optimal sites for Carbon Capture and Utilization (CCU) facilities based on facility emissions data.

Project Overview
Global climate change driven by CO2 emissions necessitates the development of technologies like Carbon Capture and Utilization (CCU). This project aims to leverage machine learning techniques to identify ideal industrial locations for CCU installations in the United States. By clustering emissions data and population density, we provide insights into locations with high CO2 capture potential and market viability for CO2-based products.

Thesis Objective
The goal of the project is to utilize machine learning methods to:

Analyze emissions data from industrial facilities in the U.S.
Identify optimal locations for CCU implementations using clustering techniques.
Highlight regions with high CO2 emissions and significant nearby population to ensure market availability for CO2-derived products.
Methods
The project involves two main unsupervised machine learning algorithms:

K-Means Clustering: Used to group facilities based on CO2 emissions percentage and population within a 100 km radius.
Spectral Clustering: Implemented to explore alternative groupings based on more complex relationships within the dataset.
Dataset
The primary data comes from the U.S. Environmental Protection Agency (EPA), which includes detailed facility-level emissions data. Additional data, such as population centers within 100 km, was extracted from the 2021 U.S. Census.

Key Features
CO2 Emissions: Total reported direct CO2 emissions from facilities.
Population Proximity: Number of people living within a 100 km radius of each facility, indicating potential markets for CO2-derived products.
Industry Type: The type of industry (power plants, steel mills, refineries, etc.) to target high-potential sectors for CCU.

Results
The clustering results highlight several key industrial clusters, including steel mills and power plants, which offer high potential for CCU due to significant CO2 emissions and proximity to dense population areas. These clusters provide viable candidates for further exploration into the economic feasibility of CCU installations.

Tools and Libraries
Python: Core language used for data processing and machine learning.
Jupyter Notebook: Used for developing and executing the code.
Pandas, NumPy, and Seaborn: Essential libraries for data manipulation and visualization.
Scikit-learn: For implementing machine learning algorithms.

Conclusion
This project demonstrates how machine learning can be applied to environmental technology to identify ideal sites for CCU, contributing to the global efforts toward CO2 reduction and climate change mitigation.

Future Work
Incorporation of more features like transportation infrastructure and regulatory policies to refine site selection.
Exploration of other unsupervised learning algorithms to improve clustering accuracy.
Expanding the scope to include facility data from other regions like the EU or Asia.
References
EPA Facility-level Emissions Data (2023)
U.S. Census Bureau (2021)
