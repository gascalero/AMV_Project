This project involved a comprehensive study to identify key dimensions shaping national innovation and economic performance across European Union (EU) countries. The primary goal was to understand the relationships between technological capacity, human capital development, and economic strength, and how these factors drive competitiveness and development.

Here's a summary of the project:

*   **Objective**: The study aimed to answer two key questions:
    *   What are the most significant dimensions shaping innovation and economic performance in EU countries?
    *   How do these dimensions differentiate countries in terms of competitiveness and development?
    The ultimate goal was to provide policymakers with insights to bridge developmental disparities and enhance sustainable growth.

*   **Data Used**: The study analyzed 11 carefully selected variables for the year 2022, reflecting key dimensions such as infrastructure, research intensity, human capital, technological readiness, and economic performance. Data was sourced from trusted platforms like Eurostat and the World Bank. Examples of variables include R&D personnel, government expenditure on education, AI preparedness, productivity, and GDP per capita.

*   **Data Treatment and Analysis Tools**:
    *   **Microsoft Excel** was used for preprocessing and merging the dataset.
    *   **SAS Enterprise Guide** was extensively used for statistical analyses. Outlier identification and analysis, as well as the generation of Box-and-Whisker Plots, were performed using the SAS program and its Summary Statistics task. All variables were standardized using SAS to account for varying scales and ensure comparability before further analysis.

*   **Methodologies Employed**:
    *   **Factor Analysis**:
        *   **Principal Component Factoring (PCF)** was chosen and performed using **SAS Enterprise Guide** to identify underlying factors responsible for correlations between indicators.
        *   An iterative approach involving multiple trials was used to remove variables based on multicollinearity and weak associations.
        *   The **Kaiser-Meyer-Olkin (KMO) measure** confirmed the data's suitability for Factor Analysis, with an overall MSA value of 0.665 being tolerable.
        *   **Kaiser’s Criteria**, Pearson's method, and the Scree Plot method all suggested retaining **two factors**.
        *   **Varimax rotation** was applied to improve interpretability.
        *   The two identified factors were labeled:
            *   **Factor 1: "Innovation and Knowledge"** (accounting for 44.41% of variance), which includes variables related to a country’s readiness and capacity in innovation, knowledge, and technological development.
            *   **Factor 2: "Economic Performance and Market Dynamics"** (accounting for 30.80% of variance), which predominantly consists of variables highlighting a country’s economic performance and market dynamics.
        *   Together, these two factors explain **75.21% of the total variance**.

    *   **Cluster Analysis**:
        *   Performed to group countries based on their factor scores and also using the original 11 variables.
        *   A **hierarchical clustering approach** (Ward’s Method) was initially used to determine the optimal number of clusters.
        *   Subsequently, a **non-hierarchical method, specifically k-means**, was applied using the identified number of clusters as a parameter.
        *   The analysis on factor scores resulted in **three distinct clusters**. The cluster analysis using the original 11 variables also identified **three clusters**, which were **identical in composition** to those found using factor scores, confirming the factors' strong representation of the original data.

*   **Key Findings and Clusters**: The clustering revealed three distinct groups of EU countries:
    *   **Cluster 1: Innovation Leaders with Balanced Economies** (e.g., Sweden, Finland, Denmark): These countries achieve high scores in both Innovation and Knowledge and Economic Performance and Market Dynamics.
    *   **Cluster 2: Struggling Innovators with Underperforming Economies** (e.g., Romania, Hungary, Bulgaria): These economies show below-average performance in both innovation capacity and market competitiveness.
    *   **Cluster 3: Economic Powerhouses with Moderate Innovation** (e.g., Ireland, Luxembourg): These countries excel economically but rely less on innovation for growth, showing moderate or below-average performance in Factor 1.

*   **Conclusion and Implications**: The study's conclusions offer practical suggestions for policymakers to enhance innovation capacity, improve economic performance, and reduce disparities across the EU. For instance, Innovation Leaders should leverage their strengths for long-term economic growth, struggling innovators need substantial policy interventions, and Economic Powerhouses can benefit from increased investment in innovation to sustain long-term growth.
