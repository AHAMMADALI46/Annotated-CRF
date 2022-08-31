# Annotated-CRF

/*CRF Annotation:
Annotating non-standard(cdm) variables into standard(sdtm)
in PDF editor
required documents
1. Protocol
2.raw datasets
3. sdtm-ig(reference)*/

/*Validation*/
We have to compare two datasets, we have to identify who is mistake and who is programming is correct
whether they are developing program according to spec right or not, whether your raw data is correct or not, terminology is correct or not.

proc compare base=prod compare=val;
run;

data prod;
set sdtm.dm;
run;

data val;
set sdtm1.dm;
run;

proc compare base=prod compare=val;
run;

data prod1;
set sdtm.dm;
run;

data val1;
set sdtm.dm;
run;

proc compara base=prod1

Pinnacle 21:
Export to excel sheet which has four tabs: Issues, rules, summary
