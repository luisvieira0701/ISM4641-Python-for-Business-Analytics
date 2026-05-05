# ISM4641-Python-for-Business-Analytics
This is a repository containing my work in the course ISM4641. I am organizing weekly folders, each with assignments and projects. I am hoping to highlight my progress as I become proficient in AI oriented Python focused for business analytics. For context, I have previous exp in Javascript (refer to other projects and scenarios from different repositories). 

Each weekly folder will have three main files:

1. Integrative Assignments - These are the projects I am working on weekly that will be graded
3. Gemini Chat History - The gemini chat history. Here you are able to see my thought process and how I am implementing code, and making projects more organized, functional, and efficient.
4. Others - The other files are likely slides or class notes I refer to when completing these projects.


## 🚀 Final Project Overview: StreamPlus Premium-Tier Upgrade Targeting

### 🎯 Business Challenge
StreamPlus Media aimed to **boost its ARPU** by encouraging Basic subscribers to upgrade to Premium. While past offers achieved an 11% conversion, they came with a significant drawback: a **2.5% increase in churn (📉 $55 LTV loss)** for non-converters. Successful upgrades, however, yielded **$96 in incremental annual revenue**. The core challenge was clear: maximize upgrade revenue while critically minimizing costly churn from untargeted offers.

### 🛠️ Technical Approach
We tackled this problem by developing a predictive model using **Python** 🐍 and essential libraries:

*   **Data Analysis (📊):** `pandas` for loading and inspection, `matplotlib` & `seaborn` for Exploratory Data Analysis (EDA).
*   **Model Building (📈):** A `Logistic Regression` model from `sklearn` was chosen for its interpretability. We used `train_test_split` with `stratify=y` to handle class imbalance.
*   **Insights & Optimization (💡):** Model coefficients were converted to **odds ratios** for actionable business insights. We prioritized **Precision** as the key metric due to the high cost of False Positives. The model was optimized to find the **optimal probability threshold** that maximizes **Net Value** (balancing $96 revenue vs. $55 LTV loss).

### ✅ Key Outcome
Our analysis revealed an optimal probability threshold of **0.31**. By targeting Basic subscribers with a predicted upgrade probability of 0.31 or higher, StreamPlus can expect a projected conversion rate of **46-47%** among contacted subscribers. This strategy dramatically reduces churn risk and significantly **maximizes Net LTV Impact**. The model identifies heavy device users, highly engaged content viewers, and long-term subscribers as prime candidates for successful targeting.

