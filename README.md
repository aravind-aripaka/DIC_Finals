# Data Intensive Computing (DIC) Finals

## Lecture 2: **“Data Intensive” Computing**  
### Dr. Naeem Maroof  
**Fall 2024**  
**Reference**: _Doing Data Science, Chapter 1_

---

### **What is Data Intensive Computing?**  
- **The 4 Vs of Big Data**:  
  - **Volume**: Sheer size of data  
  - **Velocity**: Speed of data generation  
  - **Variety**: Different types of data (structured, unstructured, streaming)  
  - **Veracity**: Uncertainty in data  

- **Processing? (Why)**:  
  Intelligence for decision-making.

- **Key Concepts**:  
  - Storage models  
  - Processing models  
  - Big Data  
  - Analytics and cloud infrastructures  

---

### **Example DI Applications**  
1. **Search engines**: Google  
2. **Recommendation systems**: Netflix, Amazon  
3. **Biological systems**: Genomics (Analysis, query/search)  
4. **Space exploration**  
5. **Financial analysis**

---

### **High-Level Goals**  
1. **Understand** the foundations of data analytics (Big Data).  
2. **Learn** to apply statistical and ML models.  
3. **Acquire new skills**:  
   - Coding  
   - Analysis  
   - Interpretation  
   - Visualization/presentation  
4. **Explore** Data Storage and Processing models.  
5. **Leverage cloud** for data storage and deployment.

---

### **Big Data (BD) Pipeline**
1. Data analytics  
2. Infrastructure and algorithms  
3. Emerging challenges: **streaming data**  

---

### **BD Skillset**
Data Intensive Computing requires diverse skills:  
- Domain expertise  
- Statistical analysis  
- Machine learning (ML)  
- Coding proficiency  
- Distributed computing  
- Visualization and communication  

---

### **Characteristics of DIC Applications**  
- Big Data: Diverse and voluminous  
- Continuous **flood** of data from varied sources  

#### **Types of Data**:  
1. **Structured**: Known formats  
2. **Unstructured**: No fixed format (e.g., social media, text)  
3. **Streaming**: Constant flow of data  

---

### **Deluge of Data**  
#### **Examples**:  
1. **Bioinformatics Data**:  
   - 3.3 billion base pairs in a human genome  
   - Protein sequences and behavior analysis  

2. **Internet Data**:  
   - Web logs, Facebook, Twitter, maps, blogs  

3. **Financial Applications**:  
   - Trend analysis and deeper knowledge discovery  

4. **Healthcare**:  
   - Patient, drug, and treatment data  

5. **Astronomy**:  
   - Hubble Telescope images of galaxies  
   - [Sloan Digital Sky Survey (SDSS)](https://www.sdss.org/)

---

### **Approaching Challenges in Data Intensive Computing**
#### **1. Algorithmic Approaches**:  
   Develop scalable and efficient algorithms.

#### **2. High-Performance Computing (HPC)**:  
   - **Example**: Frontier Machine at ORNL (over 8 million cores, 1+ exaflop).  
   - **Tools**: MPI, OpenMP.  

#### **3. GPGPU Programming**:  
   - NVIDIA GPUs for general-purpose tasks.  

#### **4. Statistical Packages**:  
   - R, Python with parallel threading.  

#### **5. Machine Learning**:  
   - Advanced algorithms on supercomputers.  

#### **6. Hadoop & Spark**:  
   - MapReduce and in-memory models.  

---

### **Cloud Computing for Big Data**
- **Cloud as a facilitator**:  
  - Processors, storage, OS, monitoring, clusters as a service.  

#### **Models**:  
1. **Platform (PaaS)**: Microsoft Azure  
2. **Software (SaaS)**: Google App Engine  
3. **Infrastructure (IaaS)**: AWS  

---

### **Key Quote**
> _“In pioneer days they used oxen for heavy pulling. When one couldn’t budge a log, they didn’t try to grow a larger ox. We shouldn’t be trying for bigger computers, but for more systems of computers.”_  
— Grace Hopper  

---

## Lecture 3: **Data Strategy**
**References**: _Doing Data Science, Chapters 1 & 2_

---

### **Components of a Data Strategy**
1. **Data integration** and metadata  
2. **Modeling**  
3. **Roles and responsibilities**  
4. **Performance metrics**  
5. **Security and privacy**  
6. Management of:  
   - Structured data  
   - Unstructured data  
7. Business intelligence  
8. Data analysis and visualization  

---

### **Steps in a Data Strategy**
1. **Frame the Problem**:  
   - Define use cases, stakeholders, and outcomes.  

2. **Understand the Data**:  
   - Explore size, sparsity, outliers, and sampling methods.  

3. **Feature Extraction**:  
   - Identify important data points.  

4. **Modeling**:  
   - Use probabilistic models and statistical inference.  

5. **Design, Code, and Deploy**:  
   - Use SW engineering principles.  

6. **Present Results**:  
   - Effective visualization and interaction.  

7. **Iterate**:  
   - Refine based on feedback.  

---

### **New Kinds of Data**
- Text: Tweets, articles, books  
- Records: JSON, logs  
- Geo-location data  
- Sensor and network data  
- Multimedia: Images, videos  

---

### **Statistical Inference in Big Data**
- From data → Build models → Derive insights  
- Statistical estimators predict patterns in stochastic processes.  

---

### **Exploratory Data Analysis (EDA)**
- Use plots, graphs, histograms to understand distributions, time series, and relationships.  

---

### **Visualization Tools**
- **d3.js**  
- **Tableau**  
- Python libraries: Matplotlib, Seaborn  

---

### **Iterative Process**
- Data Science is iterative. Revise models based on feedback and analysis.  

---


### **Content**  
- So far:  
  - Big Data (BD)  
  - Data Science (DS)  
  - Profiles, Characteristics  
  - BD Pipeline  
- Statistical Inference  
- Exploratory Data Analysis (EDA)  

---

## **Statistical Inference**  

### **Key Concepts**:  
1. **Randomness and Uncertainty**:  
   - Simplify large data (Excel sheets, databases) into concise, comprehensible forms.  

2. **Population vs Sample**:  
   - Statistical estimators help extract meaning and insights from data.  

---

## **Data Strategy: Steps to Consider**
1. **Frame the Problem**:  
   - Define the use case clearly.  

2. **Understand the Data**:  
   - Perform EDA to identify patterns and characteristics.  

3. **Extract Features**:  
   - Determine important data points based on the problem.  

4. **Model the Data**:  
   - Analyze data to extract insights and relationships.  

5. **Design, Code, and Experiment**:  
   - Use tools for data cleaning, extraction, plotting, and analysis.  

6. **Present and Test Results**:  
   - Create effective visuals and interactive elements for human and system stakeholders.  

7. **Iterate**:  
   - Refine based on feedback and new insights.  

---

### **Example (Data Science from Scratch, Ch. 5)**  
- Divide data scientists into bins based on their location (e.g., East Coast vs West Coast).  
- Find the average number of friends per bin.  

---

## **Extracting Features**  

### **Steps**:  
1. **Clean Data** → **Perform EDA** → **Extract Features**.  
2. Filter only important fields (e.g., `json` data).  

### **Example**:  
- For a tweet: Only **location** and **temperature** may be relevant.  
- Use case defines what fields to extract (e.g., age, gender).  

---

## **Modeling**  

### **What is a Model?**  
- An abstraction, structure, or equation to represent data relationships.  
- **Example**: Linear model: \( y = \beta_1 + \beta_2x \).  

### **Building Models**:  
1. Start with EDA.  
2. Use visualizations (histograms, scatter plots) to identify relationships.  
3. Gradually refine models from simple to complex.  

---

### **Probability Distributions**:  
- **Examples**:  
  - Normal, Uniform, Cauchy, Chi-square, Exponential, Weibull, Lognormal.  

#### **Key Properties**:  
1. Continuous density functions map \( p(x) \) to a positive real number.  
2. Integrating \( p(x) = 1 \).  
3. **Joint Distributions**: \( p(x, y) \) models the probability of \( x \) and \( y \) occurring.  
4. **Conditional Distributions**: \( p(x|y) \) models \( x \) given \( y \).  

---

### **Fitting a Model**:  
1. Estimate parameters from observed data.  
2. Use optimization algorithms like Maximum Likelihood Estimation (MLE).  
3. Avoid **overfitting** and **underfitting**.  

---

## **Design, Code, Deploy**  

### **Principles**:  
1. Design before coding.  
2. Follow software engineering best practices.  
3. Document the process inside and outside the code.  

---

## **Present the Results**  

### **Visualization Tools**:  
- [d3.js](https://d3js.org/)  
- [Tableau](https://www.tableau.com/academic)  
- Python libraries (e.g., Matplotlib, Seaborn).  

### **Best Practices**:  
1. Annotate graphs and visuals effectively.  
2. Provide interactive plots for deeper insights.  
3. Creativity is key—tailor visuals to the audience.  

---

## **ITERATE!**  
- Refine every step based on feedback and insights.  
- Data science is an **iterative process**.  

---

## **EDA & Data Cleaning**

### **EDA (Exploratory Data Analysis)**  

#### **Steps**:  
1. Analyze distributions, time-series, and relationships.  
2. Plot histograms and compute summary statistics (mean, min, max, quartiles).  
3. Identify and handle outliers.  

#### **Goals**:  
- Gain intuition about data.  
- Check sanity of scales and formats.  
- Fix missing or erroneous data.  

---

### **Data Cleaning and Munging**  

#### **Challenges**:  
- Real-world data is often dirty:  
  - Missing or incomplete.  
  - Contains errors.  
  - Improperly formatted.  

#### **Steps**:  
1. Clean up formatting.  
2. Remove nonsensical entries (e.g., $0 sale prices).  
3. Extract relevant columns.  

---

### **Using Pandas for Cleaning and Munging**  

#### **Key Features**:  
1. Stores structured data in a `DataFrame`.  
2. Reads data from common formats (e.g., `csv`).  
3. Provides powerful operations for filtering, combining, and exploring data.  
4. Integrated with Matplotlib for quick plotting.  

---

### **End Notes**
- Embrace iteration.  
- Data analysis is an evolving process.

# Data Intensive Computing (DIC) Finals

## Lecture 6: **Modeling**  
### Dr. Naeem Maroof  
**Fall 2024**

---

## **Content**
1. Exploratory Data Analysis (EDA)  
2. Modeling  

---

## **EDA**
### **Key Steps**:
1. **Formatting**:  
   - Collect, clean, remove, fill missing values, identify outliers, iterate.  

2. **Summarize**:  
   - Compute stats, plot histograms, examine correlations.  
   - Develop intuition about the data.  

---

## **Modeling**  

### **Purpose**:  
- Start deriving useful information from the data.  

### **Two Types of Algorithms/Models**:  
1. **Optimization for Parameter Estimation**:  
   - Estimate parameters of the process generating the data.  
   - Use resulting functions to predict new outcomes.  
   - Quantify uncertainty and assess the quality of predictions.  
   - **Examples**:  
     - Least Squares  
     - Newton's Methods  
     - Stochastic Gradient Descent  

2. **Machine Learning Algorithms**:  
   - Predict, classify, and cluster.  
   - Typically do not measure uncertainty but focus on accuracy.  
   - Basis for AI.  

---

### **Models vs Algorithms**
- **Models**:  
  - Rooted in mathematics and statistics.  
  - Equations that attempt to model the underlying process.  
  - Capture uncertainty.  

- **Algorithms**:  
  - Rooted in computer science and machine learning.  
  - Steps designed to achieve accurate predictions.  
  - Often ignore the underlying process.  

---

## **Linear Regression**
- **Definition**: A simple relationship between two (or more) variables.  
  <code>y</code> (dependent variable) is **linearly** related to <code>x</code> (independent variable).  
  - **Equation**:  
    <pre>y = β₀ + β₁x</pre>  

- **Why Linear Regression?**  
  - Linear relationships are often a good starting point.  
  - Even if the relationship isn't linear, linear regression can provide insights.  

---

### **Examples**
1. **Subscriber Revenue**:  
   - Monthly revenue (<code>y</code>) and subscriber count (<code>x</code>):  
     <pre>y = 25x</pre>  
     (subscription price).  

2. **Friends vs Time Spent**:  
   - Data: Time spent on a social media site vs new friends added.  
   - Observations:  
     - A generally linear relationship exists.  
     - **Goal**: Capture both **trend** and **variation**.  

---

### **Fitting a Model**  
- **Objective**: Find values for <code>β₀</code> and <code>β₁</code> that minimize the error.  
- **Method**:  
  - Minimize the sum of squared vertical distances between points and the line:  
    <pre>Minimize: Σ (yᵢ - (β₀ + β₁xᵢ))²</pre>  
  - This is known as **least squares estimation**.  

---

### **Adding Variability**  
- **Reality**: Data has variability.  
- Add an error term <code>ϵ</code>:  
  <pre>y = β₀ + β₁x + ϵ</pre>  
  - **Noise (<code>ϵ</code>)**: Represents unexplained variation.  
  - Assumption: <code>ϵ ~ N(0, σ²)</code>.  

- **Probability Distribution**:  
  <pre>p(y|x) ~ N(β₀ + β₁x, σ²)</pre>  
  - <code>σ²</code>: Mean squared error of the residuals.  

---

### **Evaluating the Model**
- **Key Metrics**:  
  1. <code>R²</code>: Proportion of variance explained by the model.  
     - High <code>R²</code> = better fit.  
  2. **p-values**: Test the significance of coefficients.  
     - Low p-values = significant predictors.  
  3. **Cross-Validation**:  
     - Split data into training and test sets.  
     - Fit the model on training data, compute errors on test data, and check consistency.  

---

### **Extending the Model**  
1. **Add Predictors**:  
   - Extend to multiple regression:  
     <pre>y = β₀ + β₁x₁ + β₂x₂ + ... + ϵ</pre>  

2. **Transform Predictors**:  
   - Consider non-linear relationships:  
     <pre>y = β₀ + β₁x + β₂x² + ...</pre>  
   - Reframe <code>x²</code> as <code>z</code>: Perform linear regression on <code>z</code>.  

---

## **Practical Implementation**
- Python libraries like `scikit-learn` provide tools for regression.  
- Evaluate models using metrics such as mean squared error, <code>R²</code>, and p-values.  
- Cross-validation ensures generalizability of the model.

--- 

**End Notes**  
- Start simple, iterate, and build upon the initial model.  
- Validate models rigorously with appropriate evaluation metrics.  
- Adapt and refine based on insights and new predictors.  


