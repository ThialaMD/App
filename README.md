# Medical Software Development
Übung 1:
> **Programming Task:** Gene Analyzer (Command-Line Tool)

This project is a command-line tool designed to analyze gene data fetched from the NCBI database. 

## Data Source & Setup

The tool processes the official NCBI gene information file. You can download the latest dataset here:
* 📄 **Dataset:** [NCBI gene_info.gz](https://ftp.ncbi.nlm.nih.gov/gene/DATA/gene_info.gz)

> **Note:** The `gene_info.gz` file is updated daily by NCBI. As a result, exact counts and analysis outputs will vary depending on when the data is fetched.

---

##  Analysis Questions & Results

The following results were generated using a **Pandas-based analysis** script.

### 1. Total Genes Listed
* **Question:** How many genes are listed in total?
* **Result:** `66,738,404` genes

### 2. Homo Sapiens Genes
* **Question:** How many genes are listed specifically for the species *Homo Sapiens*?
* **Result:** `193,796` genes

### 3. Unique Gene Types
* **Question:** List all available gene types in the dataset.
* **Result:** The dataset contains the following **12 unique gene types**:
  * `biological-region`
  * `miscRNA`
  * `ncRNA`
  * `other`
  * `protein-coding`
  * `pseudo`
  * `rRNA`
  * `scRNA`
  * `snRNA`
  * `snoRNA`
  * `tRNA`
  * `unknown`

### 4. Most Frequent Gene Type
* **Question:** Which gene type occurs the most?
* **Result:** **`protein-coding`** with `52,487,385` occurrences.
