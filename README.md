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
