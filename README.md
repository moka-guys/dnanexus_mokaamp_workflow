# dnanexus_mokaamp_workflow

### v1.3 
- remove lofreq variant caller and VCF filtering stage
- change instance type of preprocessing app (increase memory)
- Add ingenuity import app

## v1.4
Incorporate varscan_v1.7 and mpileup_coverage_v1.0

## v1.5 
remove IVA import app

## v1.6
Replaced VarDict 1.3 with VarDict v1.3.2 & varscan2_v1.7 with varscan2_v1.7.1
New versions include Genome Ref in VCF header to allow upload and processing by QCI. 

## v1.7
replaced varscan v1.7.1 with v1.7.2 which allows for samplename to be given as a input

## v2.0
This is an update from v1.6. BAMclipper has been replaced by ampliconfilter. an obsolete version of varscan is used (v1.7.1) so this workflow will be immediately superceeded by v2.1.

## v2.1
Varscan updated to v1.7.2 from an obselete version (v1.7.1).