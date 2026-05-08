# Pandas Library: Professional Reference

**Version**: 2.0+  
**Repository**: [github.com/pandas-dev/pandas](https://github.com/pandas-dev/pandas)  
**Documentation**: [pandas.pydata.org/docs](https://pandas.pydata.org/docs/)  

---

## 1. Overview

Pandas is a BSD-licensed open-source library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language. It is a foundational component of the modern data science ecosystem.

### 1.1 Core Competencies

| Capability | Description |
|------------|-------------|
| **Data Wrangling** | Cleaning, transforming, and reshaping structured data |
| **Analytical Operations** | Grouping, aggregation, statistical analysis |
| **Time Series** | Date range generation, frequency conversion, moving window statistics |
| **I/O Handling** | Interfacing with CSV, Excel, JSON, Parquet, SQL databases, and more |
| **Missing Data** | Flexible handling of NaN, NA, and null values |

### 1.2 Primary Data Structures

| Structure | Dimensionality | Heterogeneous | Mutability | Use Case |
|-----------|---------------|---------------|------------|----------|
| `Series` | 1D | Yes | Yes | Labeled array for column/row data |
| `DataFrame` | 2D | Yes | Yes | Tabular data with row/column indices |
| `Index` | 1D | No | Immutable | Axis labels and metadata |

---

## 2. Installation & Environment

### 2.1 Production Installation

```bash
# Minimal production install
pip install pandas

# Full data science stack
pip install pandas numpy matplotlib seaborn scipy

# Conda (recommended for enterprise)
conda install pandas numpy -c conda-forge
