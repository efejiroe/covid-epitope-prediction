# covid_epitope_prediction
COVID Epitope Prediction for Vaccine Antibody Discovery
INTRODUCTION
About the case
B-cells form an essential part of the adaptive immune system, as they are capable of providing long-term protection against pathogens and harmful molecules they have adapted to. They induce antigen-specific immune responses in-vivo by producing large amounts of antigen-specific antibodies by recognizing the subregions (epitope regions) of solvent antigen proteins of pathogens. Predicting of epitope regions on new infectious pathogens e.g. the COVID19 virus is beneficial for the design and development of vaccines aimed to induce antigen-specific antibody production by significantly reducing time and effort.

About the Data
The data is was collected from, and at the time of this publishing, is freely available as a published data set originally provided from The Immune Epitope Database(IEDB) and UniProt. The data set comprises of b-cells (input_bcell.csv), sars (input_sars.csv) and covid (input_covid.csv) specific epitopes and their protein characteristics. The former two, with values of known antibody activity, are merged to form the training set. No warranties exist regarding the correctness of the data, and there is disclaimer for liability for damages resulting from its use. Unrestricted permission regarding the use of the data was also not provided especially since some data may have been covered by patents or other rights.

About the Technology

DATA EXPLORATION
These data_exp notebook does the following:
1. An assessment on the quality of the data set. The data came already pre-cleaned so no missing values were expected as demonstrated.
2. Feature importance.
3. Value distribution of the features of the data set.
