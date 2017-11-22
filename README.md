# SimRVPedigree---Supplementary-Data
### Data Sets From "Simulating Pedigrees Ascertained for Multiple Disease Affected Relatives"

## Data Sets
* RVPedDat
* PopRVSegDat
* FollowUpDat

# RVPedDat
This is a .csv formatted data set that provides the simulated pedigrees described in *Results: Applications.*

The variables included in this data set are described as follows:

Variable | Description
-------- | -------------
FamID | family identification number
ID | individual identification number
Sex | gender identification; if male sex = 0, if female sex = 1
dadID | identification number of father
momID | identification number of mother
affected | disease-affection status
DA1 | paternally inherited allele at the assumed disease locus: DA1 = 1 if rare variant is present, and 0 otherwise
DA2 | maternally inherited allele at the assumed disease locus: DA2 = 1 if rare variant is present, and 0 otherwise 
birthYr | the individual's birth year
onsetYr | the individual's year of disease onset, when applicable, otherwise NA
deathYr | the individual's year of death, when applicable, otherwise NA
RR | the individual's relative-risk of disease
available | availability status
Gen | the individual's generation number relative to the eldest founder.  For the eldest founder Gen = 1, for his or her offspring Gen = 2, etc.
proband | proband status

   
# PopRVSegDat
This is a .csv formatted data set that provides the summarized familial rare-variant segregation data discussed in *Results: Applications: Proportion of Ascertained Pedigrees Segregating a Causal Variant*.

The variables included in this data set are described as follows:
Variable | Description
-------- | -----------
GRR | genetic relative-risk for carriers of the rare causal variant.
p_c | carrier probability of the causal variant
n_2 | number of pedigrees ascertained with 2 or more disease-affected relatives
g_2 | number of pedigrees segregating a causal variant with 2 or more disease-affected relatives
n_3 | number of pedigrees ascertained with 3 or more disease-affected relatives
g_3 | number of pedigrees segregating a causal variant with 3 or more disease-affected relatives
n_4 | number of pedigrees ascertained with 4 or more disease-affected relatives
g_4 | number of pedigrees segregating a causal variant with 4 or more disease-affected relatives
n_5 | number of pedigrees ascertained with 5 or more disease-affected relatives
g_5 | number of pedigrees segregating a causal variant with 5 or more disease-affected relatives

# FollowUpDat
This is a .csv formatted data set that provides the simulated pedigrees described in Supplement to Simulating Pedigrees Ascertained for Multiple Disease-Affected Relatives.

The variables included in this data set are described as follows:

Variable | Description
-------- | -------------
FamID | family identification number
ID | individual identification number
Sex | gender identification; if male sex = 0, if female sex = 1
dadID | identification number of father
momID | identification number of mother
affected | disease-affection status
DA1 | paternally inherited allele at the assumed disease locus: DA1 = 1 if rare variant is present, and 0 otherwise
DA2 | maternally inherited allele at the assumed disease locus: DA2 = 1 if rare variant is present, and 0 otherwise 
birthYr | the individual's birth year
onsetYr | the individual's year of disease onset, when applicable, otherwise NA
deathYr | the individual's year of death, when applicable, otherwise NA
RR | the individual's relative-risk of disease
available | availability status
Gen | the individual's generation number relative to the eldest founder.  For the eldest founder Gen = 1, for his or her offspring Gen = 2, etc.
proband | proband status


# References
Simulating Pedigrees Ascertained for Multiple Disease-Affected Relatives