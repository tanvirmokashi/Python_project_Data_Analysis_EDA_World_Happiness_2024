# World Happiness Dataset - Exploratory Data Analysis (EDA)

## Objective / Abstract

This project analyzes the **World Happiness Dataset** to uncover trends and relationships between happiness scores and various socio-economic factors. Key objectives include:

- Understanding the factors influencing happiness scores across countries.
- Exploring the relationship between GDP, social support, health, and other indicators on happiness.
- Identifying patterns to support policies that improve well-being.

The analysis aims to provide actionable insights for policymakers and organizations interested in global well-being metrics.

---

## Dataset Summary

The dataset comprises **143 rows** and **11 key columns** detailing happiness scores and related socio-economic factors across countries. Key columns include:

| **Column Name**               | **Description**                                      |
|--------------------------------|----------------------------------------------------|
| `Country name`                | Name of the country                                |
| `Happiness score`             | Overall happiness score (renamed from `Ladder score`) |
| `Log GDP per capita`          | Logarithmic GDP per capita                         |
| `Social support`              | Support received by individuals                   |
| `Healthy life expectancy`     | Life expectancy score                              |
| `Freedom to make life choices`| Measure of freedom in making life decisions        |
| `Generosity`                  | Average generosity score                           |
| `Perceptions of corruption`   | Perceived level of corruption in society          |
| `Dystopia + residual`         | Additional unexplained variance in happiness score|
| `Regional indicator`          | Region grouping for each country (newly added column) |

### Excluded Columns

The following columns were excluded from the analysis due to redundancy or irrelevance:
- `Upper whisker`
- `Lower whisker`
- Other intermediary statistical values not contributing to primary analysis

---

## Questions Explored

1. **GDP and Happiness**: How does GDP per capita relate to happiness scores? *(Scatter plot)*
2. **Regional GDP Analysis**: Which regions contribute most to GDP per capita? *(Pie chart)*
3. **Social Support**: How does social support impact happiness scores? *(Scatter plot)*
4. **Corruption and Happiness**: What is the impact of perceived corruption on happiness? *(Scatter plot)*
5. **Health and Happiness**: Is there a correlation between healthy life expectancy and happiness? *(Scatter plot)*
6. **Freedom and Happiness**: How does freedom to make life choices influence happiness? *(Scatter plot)*
7. **Top and Bottom Countries**: What are the happiest and least happy countries? *(Bar chart)*
8. **Generosity Distribution**: Which countries and regions are the most generous? *(Bar chart)*
9. **Correlation Analysis**: What are the key correlations among the dataset variables? *(Heatmap)*
10. **Generosity Trends**: How do the top and bottom countries compare in terms of generosity? *(Bar chart)*

---

## Key Findings & Conclusion

### GDP and Happiness
- Countries with higher GDP per capita generally have higher happiness scores. The trend is particularly evident in developed nations, highlighting the role of economic stability in well-being.

### Regional GDP Analysis
- Western Europe had the highest GDP per capita, emphasizing its strong economic position. Sub-Saharan Africa, while contributing less, showed varied happiness scores, indicating other influential factors.

### Social Support
- Strong social support correlates with higher happiness scores across regions. Countries with robust community networks tend to rank higher in well-being metrics.

### Corruption and Happiness
- Lower perceptions of corruption correlate with higher happiness scores. Transparency and trust in governance are crucial for societal contentment, particularly in high-GDP countries.

### Health and Happiness
- Healthier life expectancy significantly boosts happiness scores. Access to healthcare and longer lifespans are integral to overall satisfaction.

### Freedom and Happiness
- Freedom to make life choices is a strong predictor of happiness. Countries with greater personal and political freedoms rank consistently higher in happiness.

### Top and Bottom Countries
- The top happiest countries include **Finland**, **Denmark**, and **Iceland**, showcasing excellent socio-economic conditions. Least happy countries like **Afghanistan** and **Zimbabwe** reflect challenges like conflict and poverty.

### Generosity Distribution
- Countries with high happiness scores often exhibit high generosity. This reinforces the connection between societal well-being and altruistic behaviors.

---

## Implications

The analysis suggests that focusing on improving economic conditions, health, and freedom while reducing corruption can positively influence happiness. Policymakers should prioritize:

- Enhancing economic growth through equitable policies.
- Promoting health and wellness programs.
- Increasing transparency to lower corruption.

---

## Tools & Libraries

- **Python**: For data analysis and visualization.
- **Pandas, NumPy**: For data manipulation.
- **Matplotlib, Seaborn**: For creating plots and visualizations.

---

## Resources

- **Dataset**: World Happiness Dataset 2024
- **Analysis Framework**: Custom Python scripts

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/world-happiness-eda.git
   ```

2. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the analysis:
   ```bash
   python happiness_analysis.py
   ```
