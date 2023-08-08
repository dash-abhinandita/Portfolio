# Work Experience
### :woman_technologist_tone1: **<u>Engineer III, Software (Bioinformatics)</u>** </br>
[Thermo Fisher Scientific](https://www.thermofisher.com/us/en/home.html){target="_blank"}, Bengaluru, India (May 2018 – Oct 2022)

#### :white_check_mark: Development of Business Analytics Dashboard
- The product stakeholders analyse the application usage metric every week to derive business insights. Previously, the exploratory data analysis was done using custom scripts to generate plots, which used to take ~3hrs per week. 
- In-order to automate the process business analytics dashboard was developed using SQL, Python, Dash Plotly to derive business insights. 
- This led to reduction in the processing time by 20X.

#### :white_check_mark: Developed Automation Framework
- AmpliSeq designer software supports input IDs from various bioinformatics databases (RefGene, dbSNP, COSMIC) for designing the primers.
- An automation testing framework was developed to compare and sync up IDs with the latest versions of these databases as used by customers.
- This led to speedy verification and validation of database synchronization meeting release timelines.

#### :white_check_mark: Chatbot for AmpliSeq product support
- AmpliSeq designer software has multiple product offerings and selection of the product is very confusing for the novice users. The idea of this project was to a develop a chatbot that would work as a SME or provide a guided wizard for product selection. This was developed as a POC as part of hackathon and won the runner’s up award across 30 teams globally.
- The training and a validation dataset were prepared using existing product documents (.txt, pdf and markdown as input datasets.
- The NLP model was built using transformers-based pretrained BERT algorithm for question and answering system.
- Application was demonstrated using dockerized Flask web server

#### :white_check_mark: Gene caching
- The turnaround time (TAT) for any large design (>500 kb) in AmpliSeq designer depends on the number of genes processed by the pipeline deployed in AWS Kubernetes cluster. On an average, it takes >24 hours for large designs to get completed. So, gene caching approach was implemented to reduce the TAT.
- Performed data analyses and visualizations to identify frequently submitted genes from AWS RDS using SQL server.
- Cached the predesigned amplicons for those genes.
- Led to 8X reduction in TAT 
- Reduced cost of AWS services by avoiding the execution of the pipeline for cached genes

### :woman_scientist_tone1: **<u>Bioinformatics Scientist (Team Lead)</u>**<br> 
[Genotypic Technology Pvt. Ltd.](https://www.genotypic.co.in/){target="_blank"}, Bengaluru, India (Jan 2014 – May 2018)
#### :white_check_mark: Management of large-scale genomic data analysis projects
- Led and mentored the Next Generation Sequencing (NGS) analysis team of 5 members.
- Handled >400 NGS analysis projects over a span of 4.5 years. 
- Communicated with clients throughout the project lifecycle from requirements gathering to report delivery.
- Prepared reports, presentations, and materials to conduct training in NGS data analysis.
- Assisted in writing research papers for the customers.

#### :white_check_mark: Genomic data analytics
- Analyzed various types of NGS data (Whole genome, Exome, Transcriptome, Metagenome, Chip-Seq, MEDIP, BS-Seq) from the Illumina sequencing platforms.
- Used various public databases such as COSMIC, dbSNP, KEEG, UniProt etc. for annotations.
- Proficiently used data analysis pipelines and software suites such as GATK, QIIME, Samtools, Bedtools, HOMER, IGV, etc.

#### :white_check_mark: Workflow automation
- Evaluation and comparison of various open-source tools and benchmarked the execution workflows using Python.
- Developed automated pipelines using Python and bash for WGS, Chip-Seq and metagenomics analysis.
- Development of customized data pre-processing workflow based on the integration of various QC metrics.

#### :white_check_mark: Statistical data analysis and visualization
- Performed descriptive and inferential statistical data analyses. 
- Generated custom interactive visualizations using Python and R/Bioconductor packages.

### :office_worker_tone1: **<u>Bioinformatics Research Fellow</u>** <br>
[C.R. Rao AIMSCS](https://crraoaimscs.res.in/){target="_blank"}, Hyderabad, India (Oct 2012 – Dec 2013)<br>

- Worked on a DST sponsored project titled "Network Biology approach in understanding of the signalling pathway with reference to membrane dynamics during exocytosis and endocytosis: Applications in Health and Disease." 
- Performed literature and database mining (HuGE navigator, OMIM, GAD) to collect the genes associated with Diabetes mellitus and Coronary Artery Disease.
- Analysed disease-gene interactions for identifying the candidate/marker genes using Human Protein Reference Database (HPRD) and CentiBiN, CytoScape and R igraph packages.

