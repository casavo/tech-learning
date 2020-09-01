# Data Science

## What is Data Science?

"_Data Science_" is a largely overrated term (probably a buzzword) to describe the activity of **extracting value from data**.

Actually Data Science only account for less than half of the process but the term is used to describe both the first part and the whole process. You know, naming is harder than caching invalidation.

## What are the main Data roles?

### Data Scientist

**Data science** is the discipline that find a way to extract value from data. Given a set of dataset, a **Data Scientist** explores them and prototype the process to extract value.

Data involved usually comes into the process in a raw format (CSV, TXT, ndJSON, binary) and is explored using an interactive notebook ([Jupyter](https://jupyter.org/), [Apache Zeppelin](https://zeppelin.apache.org/), [Google Colab](https://colab.research.google.com) and more). Most used languages are [Python](https://www.python.org/) and [R](https://www.r-project.org/). Most common libraries are [Pandas](https://pandas.pydata.org/) (Python), [Tidyverse](https://www.tidyverse.org/) (R).

Machine Learning could intersect with Data Science for some tasks but is a fundamentally different topic.

#### Books

- [Mining of Massive Datasets](https://www.amazon.com/Mining-Massive-Datasets-Jure-Leskovec/dp/1108476341/)
- [Python Data Science Handbook: Essential Tools for Working with Data](https://www.amazon.com/Python-Data-Science-Handbook-Essential/dp/1491912057/)
- [R for Data Science: Import, Tidy, Transform, Visualize, and Model Data](https://www.amazon.com/Data-Science-Transform-Visualize-Model/dp/9352134974)
- [Practical Statistics for Data Scientists: 50 Essential Concepts](https://www.amazon.com/Practical-Statistics-Data-Scientists-Essential/dp/1491952962)

### Data Engineer

**Data Engineering** is the discipline that starts when data science ends and transform the prototype into something of production-level quality, able to run at scale. The **Data Engineer** refactors the prototype code to match higher standard and build al the components required for the data flow (import and preprocess data, storing of results, monitoring, ...).

Input data could come, potentially, from any source (external API, databases, files, documents, ...) and results are stored using the most appropriate format, usually one of the most common in the Hadoop ecosystem (Parquet, Avro, ndJSON).

Most common languages are Python, Java and Scala. Most common tools come from the **Hadoop ecosystem**. The [Apache Hadoop](https://hadoop.apache.org/) project started in 2006 trying to reimplement [Google works](https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf). During the last decade, hundreds of project growth around that sharing the basic setting. [Apache Spark](https://spark.apache.org/) is one of the most relevant.

**DataOps** is an automated, process-oriented methodology to improve the quality and reduce the cycle time of data analytics, borrowing methods from DevOps with a different focus.

#### Books

- [The Data Engineering Cookbook](https://github.com/andkret/Cookbook)
- [Big Data: Principles and best practices of scalable realtime data systems](https://www.amazon.com/Big-Data-Principles-practices-scalable/dp/1617290343)
- [Spark: The Definitive Guide: Big Data Processing Made Simple](https://www.amazon.com/Spark-Definitive-Guide-Processing-Simple-ebook/dp/B079P71JHY/)
- [High Performance Spark: Best Practices for Scaling and Optimizing Apache Spark](https://www.amazon.com/High-Performance-Spark-Practices-Optimizing/dp/1491943203)

### Data Architect

**Data Architecture** is the discipline of designing the overall structure of Data in a company. This includes where data is ingested in the system, how is processed, where is stored, how long is retained and who is able to access, ...

The **Data Architect** talks with business stakeholder, data scientist, data engineer and tech people to design the Data pipeline according to everyone's requirements.

#### Books

- [Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems](https://www.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/1449373321)
- [Architecting Modern Data Platforms: A Guide to Enterprise Hadoop at Scale](https://www.amazon.com/Architecting-Modern-Data-Platforms-Enterprise/dp/149196927X)
- [Creating a Data-Driven Organization: Practical Advice from the Trenches](https://www.amazon.com/Creating-Data-Driven-Organization-Practical-Trenches-ebook/dp/B012UDK3KG)

## I found a different classification, why?

Data Science is a relatively new field. Ten years ago the process would have been called "_Data Mining_" but this term isn't cool anymore. Now the industry is looking for a standard and multiple terms are used as synonims. Data Scientist, Data Analyst, Data Engineer and BI Analyst could easily refer to the same profile.

Classification here is based on my personal experience and focus on minimizing overlaps between roles.
