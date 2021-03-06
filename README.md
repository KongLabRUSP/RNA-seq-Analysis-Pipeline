##  Project: RNA and DNA sequencing data analysis Shiny app
### Data Analysis: Marissa (Meinizi) Zheng, Davit Sargsyan 
### Created: 07/22/2018 

---    

## Table of Contents
[File Legend](#leg)
[Daily Logs](#logs)  

## File Legend<a name="files"></a>
### Scripts
**app_v6.R**: outsourcing functions and switch some plots to plotly 
**app_v5.R**: latest rna and dna pipeline
**app_v4.1.R**: rna-seq analysis version for statistician.     
**app_v2.R**: current (08/01/2018) version of the app that can run NextFlow script on Linux.    
**app_v1.R**: first version of the app. Can run batch files on Windows.    
**nextflow**: NextFlow program file.    
**pipeline.nf**: example NextFlow scriptwith passing arguments.    
**rna-seq-genecount.nf**: Bala's current (08/01/2018)  RNA pipeline script.    
**run.nextflow.R**: test running NextFlow script from R.     
**run_pgm.R**: test running NextFlow script from R and shinyFiles package.    
**test_run.bat**: test batch file to run from R.    
**testApp.R**: an example  of a Shiny Dashboard app.  

## Daily Logs<a name="logs"></a>


### 11/14/2018
* **app_v6** app_6 outsource functions from plot.R and data-prep.R and switch some plots to plotly 

### 10/22/2018
* **app_v5** app_v5 added DSS package UI part for DNA pipeline

### 10/15/2018
* **app_v5** app_v5 added heatmap of methyl% on gene level

### 10/08/2018
* **app_v5** app_v5 can run DNA pannels including annotation and exploratory analysis

### 09/25/2018
* **app_test1** app_test1 enabled download function, changed UI in FSTQ processing panel

### 09/18/2018
* **app_v4.1** app_v4.1 fixed plots display error and added filters and round decimal places, update FASTQ panel advanced parameter setting.

### 09/10/2018
* **app_v4** app_v4 add dispersion estimation plot and count plot in Deseq2  analysis, add multiple data normalization method in Exploratory Analysis Pannel .

### 09/03/2018
* **app_v4** app_v4 can run Deseq2 DE analysis, generate/ export result table and MA plot.

### 08/27/2018
* **app_v4** app_v4 add VennDiagram and heatmap to DEGseq analysis, add exploratory analysis with more general experiment design.

### 08/20/2018
* **app_v4** app_v4 add RNA DEGseq analysis.

### 08/09/2018
* **app_v3** app_v3 added DNA upstream pannel.

### 08/01/2018
* **app_v2** can now run NextFlow scripts (NextFlow must be installed on a Linux machine first). A dummy 'pipeline.nf' script is created and tested for passing parameter values.

### 07/27/2018
* Added folder path (using **shinyFiles** package), and ability to run batch file by clicking **Run Program** button.

### 07/26/2018
* modified RNA-seq pipeline uploaded        
* shiny app is modified with dashboard template     

### 07/21/2018
* Repository created       
* Template apps are uploaded    
