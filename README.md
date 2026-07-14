# Metabolomic signatures of SSRI exposure during neural differentiation and correlation of lysophosphatidylcholines with early symptoms of neurodevelopmental disorders
Abishek Arora,<sup>a,b,c</sup> Kristina Vacy,<sup>d,e,i</sup> Cátia Marques,<sup>f,i</sup> Mihai-Ovidiu Degeratu,<sup>a,b</sup> Francesca Mastropasqua,<sup>a,b</sup> Jenny Humphrey,<sup>a,b</sup> Xuan Ye,<sup>a,b</sup> Marika Oksanen,<sup>a,b</sup> Peter Vuillermin,<sup>d,g</sup> Anne-Louise Ponsonby,<sup>d,g</sup> Ingela Lanekoff,<sup>f,h</sup> and Kristiina Tammimies,<sup>a,b,*</sup> the Barwon Infant Study Investigator Group

<sup>a</sup>Center of Neurodevelopmental Disorders (KIND), Centre for Psychiatry Research, Department of Women's and Children's Health, Karolinska Institutet, and Child and Adolescent Psychiatry, Stockholm Health Care Services, Region Stockholm, Stockholm, Sweden.</br>
<sup>b</sup>Astrid Lindgren Children’s Hospital, Karolinska University Hospital, Region Stockholm, Stockholm, Sweden.</br>
<sup>c</sup>SciLifeLab, Department of Women’s and Children’s Health, Karolinska Institutet, Stockholm, Sweden.</br>
<sup>d</sup>Florey Institute of Neuroscience and Mental Health, University of Melbourne, Victoria, Australia.</br>
<sup>e</sup>Melbourne School of Population and Global Health, University of Melbourne, Victoria, Australia.</br>
<sup>f</sup>Department of Chemistry - BMC, Uppsala University, Uppsala, Sweden.</br>
<sup>g</sup>Murdoch Children's Research Institute, Royal Children's Hospital, and Department of Paediatrics, University of Melbourne, Victoria, Australia.</br>
<sup>h</sup>Center of Excellence for the Chemical Mechanisms of Life, Uppsala University, Uppsala, Sweden.</br>
<sup>i</sup>These authors contributed equally to this work.</br>
<sup>*</sup>Corresponding author. *E-mail address:* [kristiina.tammimies@ki.se](mailto:kristiina.tammimies@ki.se)

**Published in *eBioMedicine* (2026), DOI:** [10.1016/j.ebiom.2026.106291](https://doi.org/10.1016/j.ebiom.2026.106291) | **PubMed:** [42150307](https://pubmed.ncbi.nlm.nih.gov/42150307/) | **MetaboLights:** [MTBLS12645](https://www.ebi.ac.uk/metabolights/MTBLS12645)

## Analysis Pipeline

Thank you for showing interest in our manuscript. In this GitHub repository you will find the source code and data sets required to replicate our figures and findings using R.

### Differential Metabolomics

The [R Markdown file](SSRI_Differential_Metabolomics.Rmd) along with the relevent dataframes required for differential metabolomics analysis is included in this repository. Please refer to the methods section of the manuscript for details regarding the steps followed. In brief, differential metabolomic analysis for 189 metabolites was performed from the *in-vitro* section of the study using a mixed linear model for each selective serotonin reuptake inhibitor (fluoxetine, citalopram, sertraline and paroxetine) at each timepoint (day 5 and 28). Here, the linear model used was *lme(concentration ~ exposure, random = ~ 1 | cell line)*.
