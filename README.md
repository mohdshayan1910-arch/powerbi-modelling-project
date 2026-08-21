# 📊 Power BI Data Modeling Project

> A hands-on Power BI project focused on transforming a complex multi-table dataset into a structured, scalable, and analysis-ready data model using **Power Query, dimensional modeling, relationships, and Star Schema principles**.

---

## 📌 Project Overview

Data modeling is one of the most important foundations of an effective Power BI solution. A poorly structured model can lead to incorrect calculations, ambiguous relationships, slow performance, and difficult-to-maintain reports.

This project focuses on solving those challenges by taking a complex **multi-table business dataset** and developing a structured analytical model in Microsoft Power BI.

The project covers the complete modeling workflow, from understanding and transforming source data to designing relationships and organizing the final model using **Star Schema principles**.

The primary focus of this project is the **data model and its underlying architecture**, rather than simply creating visualizations.

---

## 🎯 Project Objectives

The main objectives of this project were to:

* Understand and analyze a complex multi-table dataset.
* Transform raw source data into analysis-ready tables.
* Identify the role and purpose of different tables.
* Separate transactional data from descriptive data.
* Design a scalable **Star Schema**.
* Create appropriate relationships between tables.
* Understand relationship cardinality and filter propagation.
* Reduce unnecessary complexity in the data model.
* Build a model suitable for reliable analytical reporting.
* Strengthen practical Power BI data modeling skills.

---

## 🗃️ Dataset

The project uses a complex business dataset containing multiple interconnected tables.

The original structure contains **23 tables**, making it useful for understanding real-world data modeling challenges such as:

* Multiple interconnected entities
* Different levels of data granularity
* Fact and dimension identification
* Relationship management
* Table organization
* Analytical model design

Rather than directly using the source structure for reporting, the tables were analyzed and reorganized into a more efficient analytical model.

---

# 🏗️ Data Modeling

## Star Schema

The final model follows the principles of a **Star Schema**, where a central fact table is connected to multiple dimension tables.

### Fact Tables

Fact tables contain transactional or measurable business information that can be aggregated for analysis.

Examples of analytical measures that can typically be derived from fact data include:

* Sales
* Quantity
* Revenue
* Cost
* Profit
* Transaction counts

### Dimension Tables

Dimension tables provide descriptive attributes used to slice, filter, and analyze the fact data.

Typical dimensions include:

* Customers
* Products
* Dates
* Locations
* Categories
* Other business entities

This structure simplifies analysis and provides a more reliable foundation for DAX calculations and Power BI reporting.

---

## 🔗 Relationships

Relationships were created between fact and dimension tables based on the appropriate business keys.

Key concepts considered during modeling include:

* **One-to-Many relationships**
* **Primary and foreign keys**
* **Cardinality**
* **Cross-filter direction**
* **Relationship paths**
* **Ambiguous relationships**
* **Active relationships**

The goal was to keep the model as simple and predictable as possible while maintaining the required analytical relationships.

---

# 🔄 Data Transformation

**Power Query** was used as the data preparation layer before the final model was created.

The transformation process included:

1. Connecting to the source data.
2. Reviewing the structure and purpose of each table.
3. Cleaning and preparing the data.
4. Reviewing column data types.
5. Removing unnecessary fields where appropriate.
6. Preparing tables for analytical modeling.
7. Loading the prepared tables into the Power BI model.
8. Establishing relationships between relevant entities.

This process helped separate **data preparation** from **data modeling**, creating a cleaner overall workflow.

---

# 🧩 Power BI Model Architecture

The overall workflow followed this approach:

```text
Raw Multi-Table Dataset
          │
          ▼
     Power Query
          │
          ▼
Data Transformation
          │
          ▼
Fact & Dimension Identification
          │
          ▼
     Star Schema
          │
          ▼
     Relationships
          │
          ▼
   Analytical Model
          │
          ▼
    Power BI Reporting
```

---

# 📊 Power BI Concepts Applied

The project provided hands-on practice with several important Power BI concepts:

### Data Preparation

* Power Query
* Data type management
* Data cleaning
* Table preparation

### Data Modeling

* Fact tables
* Dimension tables
* Star Schema
* Primary and foreign keys
* Relationships
* Cardinality
* Filter direction
* Model organization

### Analytical Layer

* Measures
* DAX fundamentals
* Aggregations
* Filtering and slicing
* Analytical reporting

---

# 🖼️ Project Screenshots

## Data Model

The final Power BI model demonstrates the relationships between the fact and dimension tables.

![Data Model](<img width="959" height="478" alt="Cleaned Model" src="https://github.com/user-attachments/assets/bc7f49b6-a714-4815-a95d-e33be694d9aa" />
)

---

# 📁 Repository Structure

```text
Power-BI-Data-Modeling-Project/
│
├── README.md
│
├── Power-BI/
│   └── Data_Modeling_Project.pbix
│
├── Dataset/
│   └── Dataset files
│
├── Screenshots/
│   ├── Data_Model.png
│   ├── Dashboard.png
│   └── ...
│
└── Documentation/
    └── Project_Notes.pdf
```

---

# 🛠️ Tools & Technologies

| Tool / Technology      | Purpose                                            |
| ---------------------- | -------------------------------------------------- |
| **Microsoft Power BI** | Data modeling and reporting                        |
| **Power Query**        | Data transformation and preparation                |
| **DAX**                | Measures and analytical calculations               |
| **Star Schema**        | Dimensional modeling                               |
| **GitHub**             | Project version control and portfolio presentation |

---

# 💡 Key Learnings

This project helped strengthen my practical understanding of how Power BI models should be designed before building analytical reports.

### Key takeaways:

* A strong data model is the foundation of reliable Power BI reporting.
* Fact and dimension tables should have clearly defined purposes.
* Star Schema generally provides a cleaner analytical structure.
* Relationship design directly affects how filters and calculations behave.
* Cardinality and filter direction must be chosen carefully.
* Data transformation and data modeling are separate but interconnected stages.
* A visually impressive dashboard is only as reliable as the model underneath it.
* Well-designed models make DAX calculations easier to build and maintain.

---

# 🚀 Project Outcome

The project resulted in a structured Power BI analytical model built from a complex multi-table source.

The final model provides:

* A clearer table structure
* Organized fact and dimension tables
* Defined relationships
* Improved analytical usability
* A foundation for scalable Power BI reporting
* Practical experience with real-world data modeling challenges

---


# 👤 Author

## Mohd Shayan

**Aspiring Data Analyst**

**Skills:** SQL • Power BI • Excel • Power Query • DAX • Data Modeling

---

⭐ **If you found this project useful, feel free to explore the repository and review the Power BI model.**
