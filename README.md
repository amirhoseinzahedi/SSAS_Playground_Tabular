# SSAS_Playground_Tabular

This repository contains a **SQL Server Analysis Services (SSAS) Tabular model** project built as a hands-on playground for learning and experimenting with tabular data modeling, OLAP structures, and DAX measures.

The model is developed in Visual Studio using the Tabular project type (`.smproj`) and includes the tabular schema definition (`Model.bim`) and solution files.

## 📌 Overview

SSAS Tabular is an in-memory analytical engine that enables fast querying of relational data using columnar storage and DAX (Data Analysis Expressions). Tabular models are commonly used for business intelligence and reporting scenarios in enterprise environments.

This project demonstrates:
- Basic tabular model structure with tables, relationships, and measures
- Import and relationships designed in the `.bim` model
- How SSAS can be used to deliver analytical datasets for reporting tools such as Power BI or Excel

## 🚀 Getting Started

To explore and work with this SSAS Tabular project:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/amirhoseinzahedi/SSAS_Playground_Tabular.git

2. **Open the solution:**

- Launch Visual Studio with the SQL Server Data Tools (SSDT) extensions installed.

- Open SSAS_Playground_Tabular.sln.

3. **Connect to a Tabular SSAS instance:**

- Ensure SQL Server Analysis Services is installed in Tabular Mode.

- In Visual Studio, right-click the project and deploy or process against your SSAS instance.

4. **Explore the model:**

- Review the Model.bim file to examine tables, relationships, calculated columns, and measures.

- Use SSMS or Power BI Desktop to connect for querying live data after deployment.

## 📊 What This Demonstrates

- Tabular modeling fundamentals (tables, relationships)

- SSAS project structure in Visual Studio

- Compatibility with modern BI tools via live connections

- Foundation for building analytical models and exploring DAX

## 📌 Notes

- This is a learning and demo project and is not tied to any production data source.

- The model can be extended with additional measures, calculated tables, and security roles as future enhancements.

## 🛠 Tools & Technologies Used

- SQL Server Analysis Services (Tabular)

- Visual Studio with SQL Server Data Tools (SSDT)

- DAX (Data Analysis Expressions)

- Analysis Services metadata defined in the .bim file format 📦

