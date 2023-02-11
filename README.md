# Website_CoreBusiness_Classification


This project is a classification problem. A company provides insurance. Regulations prevent it
from insuring certain companies. Using their domain and homepage text, I am asked to
classify the companies' core business.

The data is saved in Parquet format as a DataFrame, split into train & test (without labels). It is
constructed of three columns: Domain <text>, Homepage <text>, label <text>. I recommend
using Colab as a platform to train the model, using their free GPU instance.
  
Note that the Other class (denoted as other) is constructed of companies who’s core business is
considered legitimate by the company in terms of providing insurance, compared to the rest of the
classes which are considered as restricted (denoted as restricted).
  
Deliverables:
1. Exploratory Data Analysis (EDA)
2. Multi-Class Classification Model
3. Study of Model Bias - Given that cost of predicting a restricted company as Other is higher compared to predicting
Other as restricted.
