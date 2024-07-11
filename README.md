# Industrial-Copper-Modeling

The "Industrial Copper Modeling" notebook involves data analysis and predictive modeling on a dataset related to copper production and sales. The dataset includes various attributes such as quantity, customer information, country, status, item type, application, thickness, width, material reference, product reference, delivery date, and selling price.

**Key Findings:**

*Data Overview:*

* The dataset consists of 181,673 entries with 14 columns.
* Key columns include quantity tons, customer, country, status, item type, application, thickness, width, material_ref, product_ref, delivery date, and selling_price.

*Data Cleaning:*

* Missing values were identified in columns like material_ref, country, and application.
* Various data types were observed, with most columns being either float64, int64, or object types.

*Exploratory Data Analysis (EDA):*

* Unique values were computed for key columns.
* Data was categorized into continuous and categorical variables for further analysis.
* Visualizations and statistical summaries were used to understand data distributions and relationships.
  
*Predictive Modeling:*

* Continuous columns like quantity tons, thickness, width, and selling_price were analyzed.
* Categorical columns like customer, country, status, item type, application, product_ref, and delivery date were also considered.
* Models were created to predict key outcomes based on the available features.

> **Technologies Used:**
> * Python: The primary programming language used for data analysis and modeling.
> * Pandas: For data manipulation and cleaning.
> * Matplotlib/Seaborn: For data visualization.
> * Scikit-learn: For predictive modeling.
