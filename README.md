# DIC_Finals

```plaintext
Data Intensive Computing  
Lecture 2  
“Data Intensive” Computing  
Dr. Naeem Maroof  
Fall 2024  
Reference: Doing Data Science, Chapter 1  

---

### What is Data Intensive Computing?  
- **The 4 Vs of Big Data**: Volume, velocity, variety, veracity (uncertainty)  
- **Processing? (why)**: Intelligence for decision making  
- **Storage models, processing models**  
- **Big Data, analytics and cloud infrastructures**  

---

### Example DI Apps  
- **Search engines**: Google  
- **Recommendation systems**: Netflix, Amazon  
- **Biological systems**: Genomics (Analysis, query/search)  
- **Space exploration**  
- **Financial analysis**  

---

### High Level Goals  
1. Understand foundations of data analytics (Big Data)  
2. Learn to apply statistical and ML models (ML)  
3. Learn new skills (code, analyze, interpret, visualize/present)  
4. Learn Data Storage models and Processing models  
5. Working with cloud for data storage and deployment  

--

### BD Pipeline:  
1. **Data analytics**  
2. **Infrastructure and algorithms**  
3. **Newer challenges** (streaming data)  
---
<img width="349" alt="image" src="https://github.com/user-attachments/assets/3de8e60f-2a3b-4219-9293-50842a9a5d53">

### BD Skillset  
Data Intensive Computing requires a diverse set of skills (and no one person will likely be an expert in all of them).  

---

### Data Scientist Profiles  
#### Characteristics of DIC Applications  
- **Big Data**  
- Diverse in nature  
- Flood of data from varied sources  

---

#### Types:  
- **Structured** (known format)  
- **Unstructured** (without any format): social / textual  
- **Streaming** (constant flow)  

---

### Deluge of Data  
#### Bioinformatics data:  
From about 3.3 billion base pairs in a human genome to huge number of sequences of proteins and the analysis of behaviors  

#### The Internet:  
- Web logs  
- Facebook  
- Twitter  
- Maps  
- Blogs  
- Analytics  

#### Financial applications:  
- Volumes of data for trends and other deeper knowledge  

#### Healthcare:  
- Huge amount of patient data  
- Drug and treatment data  

#### The Universe:  
- The Hubble ultra-deep telescope shows 100s of galaxies each with billions of stars.  
- Sloan Digital Sky Survey: [https://www.sdss.org/](https://www.sdss.org/)  

---

### Example: Bioinformatics Data  
**Large Databases[1]**  
[1] [http://www.comparebusinessproducts.com/fyi/10-largest-databases-in-the-world/](http://www.comparebusinessproducts.com/fyi/10-largest-databases-in-the-world/)  

---

### How do we approach these issues?  
1. **Algorithmic**: Develop scalable/tractable algorithms  
2. **High Performance Computing (HPC)**:  
   - Frontier machine (ORNL) has over 8 million cores, over 1 exaflop  
   - Programmed with technologies like MPI, OpenMP, etc.  
3. **GPGPU programming**: General purpose graphics processor (NVIDIA)  
4. **Statistical packages**: R and/or Python running on parallel threads on powerful machines  
5. **Machine learning algorithms on supercomputers**  
6. **Hadoop**: MapReduce-like parallel processing  
7. **Spark-like approaches**: In-memory computing models  
8. **Stream processing infrastructure**: Kafka  
9. **Processing at different granularity**  

---

### Data Size:  
- **Small**  
- **Large**  

---

### Algorithms  
1. Statistical inference  
2. Machine learning  
3. Data mining  
4. Soft computing  
5. Deep learning  

---

#### Also need algorithms designed for emerging storage models and data characteristics.  

---

### “Intelligence” and Scale of Data  
- Data → Info → Intelligence  
- Set of discoveries by extracting/processing information from data  
- For good intelligence, we need a large amount of information  
- To get statistically significant information we need a large data  

---

#### Intelligent applications are invariably data-heavy, data-driven, and data-intensive:  
Examples:  
- Google search  
- Restaurant and menu suggestions  
- LinkedIn  
- Facebook friend suggestion  
- Advertisements  

---

### Data Driven  
---

### Different Types of Storage  
#### New challenges with logged large-scale data:  
- Different characteristic than transactional log  
- The data type is “write once read many (WORM)”  

---

### Other Examples:  
1. Privacy-protected healthcare and patient information  
2. Historical financial data  
3. Other historical data  

---

### Different Types of Storage  
[2] Hasan, Ragib, and Marianne Winslett. “Efficient audit-based compliance for relational data retention.” ACM Asia Conference on Computer and Communications Security (2011).  

---

### Different Types of Storage  
#### Relational file system and tables are insufficient. We need:  
1. Large <key, value> stores (files) and storage management system  
2. Built-in features for fault-tolerance, load balancing, data-transfer, and aggregation  
3. Clusters of distributed nodes for storage and computing  
4. Computing is inherently parallel  
5. Streaming systems  

---

### Big Data Concepts  
1. Google File System (GFS): The special <key, value> store  
2. Hadoop Distributed File System (HDFS): OS version (an Apache project)  

---

#### Parallel Processing of the Data Using MapReduce (MR) Programming Model  
Challenges:  
- Formulation of MR algorithms  
- Proper use of the features of infrastructure (Ex: sort)  
- Best practices in using MR and HDFS  
- Coordinating an extensive ecosystem of other components: column-based store (Hbase, BigTable), big data warehousing (Hive), workflow languages, etc.  

---

### Cloud Computing  
- **Cloud** is a facilitator for Big Data computing and is indispensable in this context.  
- It provides processors, software, operating systems, storage, monitoring, load balancing, clusters, and other requirements as a service.  
- **Cloud offers accessibility to Big Data computing.**  

---

### Cloud Computing Models:  
1. **Platform (PaaS)**: Microsoft Azure  
2. **Software (SaaS)**: Google App Engine (GAE)  
3. **Infrastructure (IaaS)**: Amazon Web Services (AWS)  
4. **Services-based application programming interface (API)**  

---

### In Summary…  
> “In pioneer days they used oxen for heavy pulling, when one couldn’t budge a log they didn’t try to grow a larger ox. We shouldn’t be trying for bigger computers, but for more systems of computers.” ~Grace Hopper  

- We have witnessed an explosion in algorithmic solutions.  
- What you cannot achieve by an algorithm can be achieved by more data.  
- Big data, if analyzed right, gives you better answers.  

---

### Data Strategy  
#### Essentially, how are you going to plan for the data challenge?  
- It is not only about big data, but data in all sizes and forms.  
- Data collections from customers used to be an elaborate task (e.g., surveys).  
- Nowadays data is available in abundance due to technological advances and social networks.  
- Data is also generated by business processes and applications.  

---

### Components of a Data Strategy  
1. Data integration and meta-data  
2. Data modeling  
3. Organizational roles and responsibilities  
4. Performance and metrics  
5. Security and privacy  
6. Structured data management  
7. Unstructured data management  
8. Business intelligence  
9. Data analysis and visualization  

---

### Data Strategy at a High Level  
1. How will you collect data? Aggregate data? What are your sources? (e.g., social media)  
2. How will you store your data? And where?  
3. How will you use the data? Analyze it? Analytics? Data mining? Pattern recognition?  
4. How will you present or report the data to the stakeholders and decision-makers? Visualization?  
```
---
Data Intensive Computing  
Lecture 3  
… Data Strategy  
---

### Review  
- **BD and 4Vs**: Intelligence, examples  
- **New models**: Storage models, processing models  
- **DICompute**: BD/DS, Math/Stat/Prob, ML, MapReduce, Spark  
- **Char**: Databases, Expert Knowledge, Algorithms, Infrastructure (storage/computing: WORM), ML Models, Vis  
- **BD skillset**: (Dom. Ex., Stat., ML, Coding, Dist.Computing, Vis /App /Comm)  
- **BD Pipeline**  

---

### Different Types of Storage  
1. Relational file system and tables are insufficient… we need:  
   - Large <key, value> stores (files) and storage management system  
   - Features for fault-tolerance, load balancing, data-transfer & aggregation  
   - Clusters of distributed nodes for storage and computing  
   - Inherently parallel computing  
   - Streaming systems  

---

### Big Data Concepts  
1. **Google File System (GFS)**: The special <key, value> store  
2. **Hadoop Distributed File System (HDFS)**: OS version (an Apache project)  

---

#### Parallel Processing of the Data Using MapReduce (MR) Programming Model  
**Challenges**:  
- Formulation of MR algorithms  
- Proper use of the features of infrastructure (Ex: sort)  
- Best practices in using MR and HDFS  
- Coordinating an extensive ecosystem of other components: column-based store (HBase, BigTable), big data warehousing (Hive), workflow languages, etc.  

---

### Cloud Computing  
- **Cloud** is a facilitator for Big Data computing and is indispensable in this context.  
- It provides processors, software, operating systems, storage, monitoring, load balancing, clusters, and other requirements as a service.  
- **Cloud offers accessibility to Big Data computing.**  

---

### Cloud Computing Models:  
1. **Platform (PaaS)**: Microsoft Azure  
2. **Software (SaaS)**: Google App Engine (GAE)  
3. **Infrastructure (IaaS)**: Amazon Web Services (AWS)  
4. **Services-based application programming interface (API)**  

---

### In Summary…  
> “In pioneer days they used oxen for heavy pulling, when one couldn’t budge a log they didn’t try to grow a larger ox. We shouldn’t be trying for bigger computers, but for more systems of computers.” ~Grace Hopper  

- We have witnessed an explosion in algorithmic solutions.  
- What cannot be achieved by algorithms, can be achieved by more data.  
- Big data, if analyzed right, gives you better answers.  

---

### Data Strategy  
- **Essentially, how are you going to plan for the data challenge?**  
- It is not only about big data, but data in all sizes and forms.  
- **Data collections** from customers used to be an elaborate task (e.g., surveys).  
- Nowadays data is available in abundance due to technological advances and social networks.  
- **Data is also generated by business processes and applications.**  

---

### Components of a Data Strategy  
1. Data integration and meta-data  
2. Data modeling  
3. Organizational roles and responsibilities  
4. Performance and metrics  
5. Security and privacy  
6. Structured data management  
7. Unstructured data management  
8. Business intelligence  
9. Data analysis and visualization  

---

### Data Strategy at a High Level  
1. How will you collect data? Aggregate data? What are your sources? (e.g., social media)  
2. How will you store your data? And where?  
3. How will you use the data? Analyze it? Analytics? Data mining? Pattern recognition?  
4. How will you present or report the data to the stakeholders and decision-makers? Visualization?  

---

### Steps to Consider  
#### 1. Frame the Problem  
- Have a standard use case format (What, why, how, stakeholders, data in, info out, challenges, limitations, scope, etc.)  
- Refer to your software engineering course.  
- **Statement of Work (SOW)**: Clearly state what you will accomplish.  

#### 2. Understand the Data  
- **Data represents traces of real-world processes.**  
- What traces we collect depends on the sampling methods.  
- Models help extract meaning and information from data: **Statistical inference.**  
- **Two sources of randomness and uncertainty**:  
  1. The process generating data is random.  
  2. The sampling process itself is random.  
- Combine statistical approach with big-data.  

**Questions to Ask**:  
- How big is the data?  
- Any outliers?  
- Missing data? How to address it?  
- Sparse or dense?  
- Collision of identifiers in different data sets?  

---

### New Kinds of Data  
1. Traditional: Numerical, categorical, or binary  
2. Text: Emails, tweets, NY Times articles, books  
3. Records: User-level data, time-stamped event data, JSON formatted, logs  
4. Geo-based location data  
5. Network data: How do you sample and preserve network structure?  
6. Sensor data  
7. Images, video, maps  

---

### Uncertainty and Randomness  
- **Uncertainty**: Lack of knowledge (e.g., weather predictions)  
- **Randomness**: Lack of predictability (e.g., rolling a die)  
- Both can be expressed by **probability theory**.  

---

### Statistical Inference  
- **From the world** → Collect data  
- **From the data** → Capture meaning through models/functions  
- **From the meaning** → Devise statistical estimators for predicting things  

#### Statistical inference:  
Development of procedures, methods, and theorems to extract meaning and information from data generated by stochastic processes.  

---

### Population and Sample  
- **Population**: Complete set of data points  
- **Sample**: Subset of the population  
- Sampling introduces biases into the data.  

---

### Big Data vs Statistical Inference  
1. **Statistical inference**: N < All  
2. **Big data**: N == All  
3. For atypical big data analysis: N == 1  

---

### Exploratory Data Analysis (EDA)  
- **EDA** provides an intuitive feel for the data.  
- Basic tools: Plots, graphs, histograms, summary stats.  
- Systematically analyze:  
  - Distributions  
  - Time series  
  - Pairwise relationships (scatter plots)  
  - Summary stats (mean, min, max, quartiles, outliers)  

---

### 3. Extracting Features  
- **Process**: Clean Data → Perform EDA → Extract Features  
- Filter only the important fields or features.  
- Often defined by problem analysis and use case.  

---

### 4. Modeling  
- Data set with two columns: y depends on x.  
- Example: y = β1 + β2x (linear relationship).  
- Probability distribution functions are building blocks of statistical models.  

---

### 5. Design, Code, Deploy  
- Design before you code: An important principle.  
- Code using best practices.  
- Documentation: Inside the code and outside.  
- State deployment steps clearly.  

---

### 6. Present the Results  
- Annotate graphs and visuals effectively.  
- Provide interactive plots for what-if conditions.  
- Tools:  
  - [d3.js](https://d3js.org/)  
  - [Tableau](https://www.tableau.com/academic)  
  - Python visualization libraries.  

---

### 7. Iterate!  
- Iterate through steps based on feedback and results.  
- Data science is an iterative process.  




