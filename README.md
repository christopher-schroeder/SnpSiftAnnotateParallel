# SnpSiftAnnotateParallel
A script for parallelized execution of SnpSift annotate.

## Example
`python
python ssap.py database.vcf.bgz sample.vcf --threads 12 > sample.annotated.vcf
`

Unused parameters are forwarded to SnpSift annotate, e.g.

`python
python ssap.py database.vcf.bgz sample.vcf --threads 12 -info AC_nfe,AN_nfe,AF_nfe,nhomalt_nfe > sample.annotated.vcf
`

