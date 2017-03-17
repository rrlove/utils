
get first *n* variants of a VCF with header intact, for example, making a test or sample file:

`grep '#' -A n yourfile.vcf`

create a BEDtools .genome file from a Picard .dict file:

`grep 'SQ' yourgenome.dict | cut -f2,3 | sed 's/[[:alpha:]]N://g' > yourgenome.genome`
