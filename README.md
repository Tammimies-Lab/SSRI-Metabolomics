# Lysophosphatidylcholines are elevated after selective serotonin reuptake inhibitor exposure during neural differentiation and correlate with early neurodevelopmental symptoms
Abishek Arora (1,2,3), Kristina Vacy (4,5#), Cátia Marques (6#), Mihai-Ovidiu Degeratu (1,2), Francesca Mastropasqua (1,2), Jenny Humphrey (1,2), Xuan Ye (1,2), Marika Oksanen (1,2), the Barwon Infant Study Investigator Group, Peter Vuillermin (4,7), Anne-Louise Ponsonby (4,7), Ingela Lanekoff (6,8) and Kristiina Tammimies (1,2,*) 

1. Center of Neurodevelopmental Disorders (KIND), Centre for Psychiatry Research, Department of Women's and Children's Health, Karolinska Institutet, and Child and Adolescent Psychiatry, Stockholm Health Care Services, Region Stockholm, Stockholm, Sweden. 
2. Astrid Lindgren Children’s Hospital, Karolinska University Hospital, Region Stockholm, Stockholm, Sweden. 
3. SciLifeLab, Department of Women’s and Children’s Health, Karolinska Institutet, Stockholm, Sweden. 
4. Florey Institute of Neuroscience and Mental Health, University of Melbourne, Victoria, Australia 
5. Melbourne School of Population and Global Health, University of Melbourne, Victoria, Australia. 
6. Department of Chemistry - BMC, Uppsala University, Uppsala, Sweden. 
7. Murdoch Children's Research Institute, Royal Children's Hospital, and Department of Paediatrics, University of Melbourne, Victoria, Australia. 
8. Center of Excellence for the Chemical Mechanisms of Life, Uppsala University, Uppsala, Sweden. 
#These authors contributed equally to this work

*Correspondence: [kristiina.tammimies@ki.se](mailto:kristiina.tammimies@ki.se)

**Available on *medRxiv* (2025)** [10.1101/2025.05.30.25328657](https://doi.org/10.1101/2025.05.30.25328657)

## Analysis Pipeline

Thank you for showing interest in our manuscript. In this GitHub repository you will find the source code and data sets required to replicate our figures and findings using R.

### Differential Metabolomics

The R Markdown file required for differential metabolomics analysis is included in this repository. Please refer to the methods section of the manuscript for details regarding the steps followed. In brief, differential metabolomic analysis for 189 metabolites was performed from the *in-vitro* section of the study using a mixed linear model for each selective serotonin reuptake inhibitor (fluoxetine, citalopram, sertraline and paroxetine) at each timepoint (day 5 and 28). Here, the linear model used was *lme(concentration ~ exposure, random = ~ 1 | cell line)*.
