# <center> **生物信息学作业** </center>

#### <p align="right"> 登峰1901 王铭宇 </p>

## homework_1

### Q1:What’s the name of gene X in Mus musculus? Its  accession number in GenBank database and  coordinates of mouse genome

|title|column|
|:------:|:------|
|gene_name|NIMA-related expressed kinase 2|
|accession_number|[NM_010892.3](https://www.ncbi.nlm.nih.gov/nucleotide/NM_010892.3?report=genbank&log$=nucltop&blast_rank=2&RID=723JFK0W016)|
|chromosome|1 H6; 1 96.94 cM|
|coordinates|191552487..191565161|

### Q2:The homolog of gene X in human, and its accession  number

|title|column|
|:------:|:------|
|homolog in human|NEK2|
|accession number|GenBank: [BT019729](https://www.ebi.ac.uk/ena/browser/view/BT019729)|

### Q3:In human, the protein product of this gene. Its  functions, sub-cellular localizations. Whether it’s an  enzyme? If so, does it have a conserved functional domain?
|title|column|
|:------:|:------|
|protein product|NIMA-related kinase 2 [Homo sapiens]|
|sub-cellular location|Isoform 1: Cytoplasm, Nucleus, nucleolus, centrosome, spindle pole, kinetochore, centromere<br>Isoform 2: Cytoplasm<br>Isoform 4: Nucleus, centrosome|
|function|Component, centrosome, condensed chromosome kinetochore, condensed nuclear chromosome, cytoplasm, cytosol, kinetochore, colocalizes_with kinetochore, microtubule, midbody, nucleolus, nucleoplasm, nucleus, protein-containing complex , spindle|



NIMA-related kinase 2 is an enzyme, which has a conserved functional domain ==STKc_Nek2== .

### Q4:Whether this gene is conserved in yeast? If so,  identify its potential homolog.

It is conserved in yeast. Its potential homolog is ==kinase [Saccharomyces cerevisiae]==.

### Q5:The 3D structural information of gene X in human,  but not mouse. It’s accession number in PDB.
|title|column|
|:------:|:------|
|**Multimeric state**|monomeric|
|**Accessible surface area:**|13200 Å^2^|
|**Buried surface area:**|700 Å^2^|
|**Dissociation area:**|350 Å^2^|
|**Dissociation energy (ΔG^diss^):**|-4 kcal/mol|
|**Dissociation entropy (TΔS^diss^):**|4 kcal/mol|
|**Interface energy (ΔG^int^):**|1 kcal/mol|
|**Symmetry number:**|1|

accession number in PDBe: [2jav](https://www.ebi.ac.uk/pdbe/entry/pdb/2jav).



## homework_2

$$ P(出|裤) = \frac{P(出)*P(裤|出)}{P(裤)} $$

$$ P(裤) = \frac{P(裤|未)*P(未)}{P(未|裤)} $$

$$ P(未|裤) = 1 - P(出|裤) $$

则$ P(出|裤) = \frac{5}{17} = 0.29 $