### Marketing campaign performance analysis

**Prosenjit Sinha**

#### Analyze the campaign data from the perspective of an ad agency.  

#### Rationale
Ad agencies want to understand what factors are impacting the campaign performance. This helps them to take corrective action, guide the advertisers to take certain measures.

#### Research Question
How is the conversion rate related to different factors like campaign type, target audience, duration, location, language etc.

#### Data Sources
I will use the marketing dataset from Kaggle: https://www.kaggle.com/code/thabresh/eda-marketing-campaign-performance/input

#### Methodology
Data cleaning: Made sure there is no column with null value. 
Date preparation: Converted Aquisition_Cost to float. Used column transformer for the categorical columns
Data understanding: Used different plotting mechanisms to understand the distribution of important columns. 
Model building: Used Linear regression, Ridge, Lasso, SVR with polynomial feature selection. Used GridSearchCV for Ridge and SVR.

#### Results
SVR/Lasso performed better than other models. Feature wise campaign type matters the most, specially Display campaigns.

#### Next steps
I want to do a similar analysis from the Company perspective as well. Fot them ROI or Aquisition_Cost makes more sense to understand how is their campaign doing.

#### Outline of project
- https://github.com/prosens/Projects/blob/main/Marketing%20Campaign%20Performance/campaign.ipynb


##### Contact and Further Information