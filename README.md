# SnpSiftAnnotateParallel
A script original invented for a parallelized execution of SnpSift annotate. Now the script is able to perform any command using vcf/bcf in parallel.

## Example for SnpSift Annotate
`python
ssap.py sample.bcf "SnpSift annotate database.vcf.bgz /dev/stdin" --threads 12
`

## License
MIT
