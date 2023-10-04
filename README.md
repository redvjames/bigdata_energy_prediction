# bigdata_energy_prediction
A Project for Big Data and Cloud Computing of Asian Institute of Management's Master of Science in Data Science 2023 

The study aims to address the need for accurate energy consumption predictions in commercial buildings, recognizing their significance in urban planning and fostering economic development. By equipping urban planners with the necessary tools and insights, energy use can be optimized, energy efficiency measures can be enhanced, and sustainable development can be promoted effectively.

The study utilized the Comstock dataset, which covers commercial building energy consumption in New York State for the year 2012. The dataset, amounting to 51.7GB, was processed using Apache Spark on AWS to handle the large volume of data efficiently.

The methodology employed in the study consisted of several steps, including data collection and loading, data cleaning and pre-processing, descriptive exploratory data analysis, predicting total energy consumption using regression models, and forecasting daily energy consumption using time series models.

The results of the study indicated the following key findings:

Regression models: The Gradient Boosting Model exhibited the lowest Mean Absolute Percentage Error (MAPE), indicating its superior performance in predicting total energy consumption. The top features influencing energy consumption were identified as weekday hours, number of stories or floors, and aspect ratio. Time series models: The analysis revealed that as the complexity of the models increased, such as moving from Random Forest to Multilayer Perceptron, the time series forecasts closely resembled the true values. The naive forecast, which relies on the previous day's record, showed a shifted behavior.

To enhance the study's insights for urban planning and drive sustainable economic growth, several key recommendations are proposed. Firstly, extending the analysis period to capture seasonal variations and long-term trends in energy consumption would provide a more comprehensive understanding of energy usage patterns. Secondly, replicating the study in the Philippines, focusing on climate-matched subsets, would offer relevant insights tailored to the local context. Additionally, replicating data collection in the Philippines to gather localized energy consumption data is crucial for informed decision-making. Integrating a building carbon footprint dataset into the analysis would enable holistic urban planning by considering environmental impact alongside energy consumption. Lastly, employing explainability methods to gain deeper insights into energy consumption patterns would inform targeted interventions and policies. By implementing these recommendations, the study can provide valuable insights for urban planning and drive sustainable economic growth.


Original Data Source

The entire ComStock dataset is also available as a public dataset on the Registry of Open Data on Amazon Web Services (AWS). The data is updated annually and managed by the National Renewable Energy Laboratory.

The dataset can be accessed here: https://registry.opendata.aws/nrel-pds-building-stock/
