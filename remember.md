escaping spaces in scp: triple backslashes

changing one column name in R, via http://stackoverflow.com/a/16490387: 

`names(df)[names(df) == 'old.var.name'] <- 'new.var.name'`

steps for using a new reference in a bwa/picard/samtools alignment pipeline:
```bash
bwa index reference.fasta
picard/CreateSequenceDictionary.jar R=reference.fasta O=reference.dict
samtools faidx reference.fasta
```

"I plotted my data and they look bizarre!":

Are you using a density plot with inappropriate range constraints?
