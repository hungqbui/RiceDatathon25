## Inspiration

Food deserts impact millions of Americans, disproportionately affecting low-income communities and contributing to long-term health issues such as obesity and diabetes. Inspired by the need for data-driven solutions, this project aims to analyze food accessibility using USDA datasets to identify key socioeconomic and health-related factors. 

## What it does

By visualizing correlations through a heatmap, we can uncover patterns that highlight the root causes of food insecurity. Understanding these relationships enables policymakers to make informed decisions to improve food access. Our goal is to provide actionable insights that can help bridge the gap between communities and fresh, healthy food.

## How we built it

We developed this project using Python and various data analysis and visualization libraries, including Pandas, NumPy, SciPy, Seaborn, and Matplotlib. First, we cleaned and merged datasets from the USDA Food Research Atlas and Food Environment Atlas to ensure consistency and accuracy. We then performed statistical analysis using NumPy and SciPy to calculate correlation coefficients, t-test, identifying key factors contributing to food deserts. Seaborn and Matplotlib were used to generate heatmaps and visualizations that highlight relationships between food access, socioeconomic status, and health indicators. Finally, we use scikit-learn to train the model for processing input and prediction. Through this structured approach, we provided data-driven insights to support policy recommendations aimed at reducing food insecurity.

## Challenges we ran into

One of the main challenges we faced was refining the data to ensure accuracy and consistency, as the datasets contained missing values and required preprocessing. Identifying the most relevant indicators for food deserts proved difficult, as multiple socioeconomic and health-related factors influence food access in complex ways. We conducted several statistical tests, but finding strong correlations between variables was challenging due to regional variations and data limitations. Additionally, balancing computational efficiency with large datasets required careful optimization to ensure smooth analysis and visualization. Despite these challenges, continuous testing and refinement allowed us to extract meaningful insights that can inform effective policy decisions.

## Accomplishments that we're proud of

We successfully identified key indicators—income levels and poverty rates—that have a strong correlation with food access, providing valuable insights into the root causes of food deserts. Through extensive data analysis and refinement, we were able to filter out less significant variables and focus on the most impactful socioeconomic factors. Our heatmaps and statistical tests effectively highlighted these relationships, making the findings both accessible and actionable. Overcoming data inconsistencies and refining our model to produce meaningful results was a major achievement. These insights can now contribute to policy recommendations aimed at improving food accessibility for underserved communities.

## What we learned

Through this project, we gained a deeper understanding of how socioeconomic factors, particularly income and poverty, directly impact food accessibility in the United States. We learned the importance of thorough data cleaning and preprocessing to ensure accurate and reliable analysis. Identifying meaningful correlations required multiple tests and iterations, reinforcing the complexity of food insecurity and the need for data-driven solutions. Additionally, we improved our skills in using Python libraries like Pandas, NumPy, SciPy, Seaborn, and Matplotlib for statistical analysis and visualization. Most importantly, this project emphasized how data science can be used to address real-world social issues and inform policy decisions.

## What's next for Hunger Heatmap

Moving forward, we plan to enhance our analysis by incorporating additional datasets, such as transportation access and local food policies, to gain a more comprehensive understanding of food deserts. We aim to refine our model by integrating machine learning techniques to predict areas at risk of becoming food deserts. Expanding our visualizations with interactive geospatial mapping tools could provide policymakers with more actionable insights. Additionally, we hope to collaborate with organizations focused on food security to apply our findings in real-world initiatives. Ultimately, our goal is to turn this project into a scalable tool that helps drive meaningful policy changes and improve food accessibility nationwide.
