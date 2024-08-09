# Analyzing-the-Impact-of-Funding-and-Number-of-Funding-Rounds-on-Startup-Survival


### Introduction

Startups play a pivotal role in driving economic growth, innovation, and job creation, particularly in a dynamic and rapidly growing economy like India. These entrepreneurial ventures often serve as engines of economic transformation, introducing disruptive technologies, creating new markets, and fostering competition. However, the journey of a startup is fraught with challenges, and not all of them succeed in reaching their full potential. Understanding the factors that contribute to the success or failure of startups is crucial for stakeholders, including investors, policymakers, and entrepreneurs.

In this project, we aim to investigate whether the survival of a startup—whether it continues operating or closes down—is influenced by two key financial indicators: the number of funding rounds it has received and the total amount of funding raised. These factors are often seen as critical determinants of a startup's ability to scale and sustain itself. However, the reality may be more complex. While funding is undoubtedly important, other variables such as market conditions, the startup's business model, management decisions, and external economic factors may also play a significant role in determining its fate.

Our analysis seeks to uncover whether there is a statistically significant relationship between the survival of a startup and its funding history, or if these financial metrics alone are insufficient to predict a startup's outcome. By exploring these relationships, we aim to provide a deeper understanding of the factors that contribute to the longevity of startups, offering insights that could help in better decision-making for future ventures in India's vibrant startup ecosystem.


### Objective
This project seeks to address the critical questions of whether there is a statistically significant difference in the mean funds raised by startups that are currently operating compared to those that have ceased operations. Additionally, we aim to investigate whether there exists a significant disparity in the number of funding rounds between currently operating startups and startups that have closed.

Dataset Credits --> https://www.kaggle.com/datasets/yanmaksi/big-startup-secsees-fail-dataset-from-crunchbase

### Top 5 key Learnings

1. **Hypothesis Formulation**:
   - The project focuses on understanding the difference in mean funds raised and the number of funding rounds between currently operating startups and those that have closed.
   - Two hypotheses are formulated for each comparison:
     - **Mean Funds Raised**:
       - Null Hypothesis (H0): No significant difference in mean funds raised.
       - Alternative Hypothesis (H1): A significant difference in mean funds raised.
     - **Number of Funding Rounds**:
       - Null Hypothesis (H0): No significant difference in the number of funding rounds.
       - Alternative Hypothesis (H1): A significant difference in the number of funding rounds.

2. **Levene's Test for Equality of Variances**:
   - Levene's test is used to check if the variances between the two groups (operating vs. closed startups) are equal. This is a crucial step before performing an independent sample t-test.

3. **Independent Sample T-Test**:
   - The independent t-test is used to compare the mean values of funds raised and the number of funding rounds between the two groups. This test helps determine if the differences observed are statistically significant.

4. **Data Exploration and Validation**:
   - The notebook includes an in-depth exploration and validation of the dataset. This step ensures that the data is suitable for analysis and that any anomalies or inconsistencies are addressed before proceeding with statistical tests.

5. **Concluding Insights**:
   - The final part of the analysis involves summarizing the findings, including whether the hypotheses were supported or rejected. These insights help to draw actionable conclusions that could inform strategies for startups.

