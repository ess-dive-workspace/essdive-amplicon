# ESS-DIVE Amplicon Data Reporting Format v1.0.0   

## About the Amplicon Data Reporting Format
ESS-DIVE’s reporting format promotes the adoption of existing metadata standards for microbiome sequencing projects while also introducing minimum metadata requirements in Earth and environmental sciences for sharing taxon tables derived from these sequencing data. In the reporting format, the sequencing metadata fields are adopted from and interoperable with the widely used Minimum Information about any Sequence ([MIxS](https://www.gensc.org/pages/standards-intro.html)) standards ([Yilmaz et al. 2011](https://doi.org/10.1038/nbt.1823)). Based on community input, the new bioinformatic metadata fields in the reporting format aim to capture the minimum information necessary to evaluate whether taxon tables can be compared or combined when parameterizing models or performing meta-analyses. With this standard, ESS researchers can manage and share the abundance profiles and recovered sequences from their sample microbiomes in consistent formats. The file formats will also enable seamless upload to a DOE platform for open-source data analysis, the Systems Biology Knowledgebase ([KBase](https://www.kbase.us/)).

The [reporting format for amplicon data](https://docs.ess-dive.lbl.gov/contributing-data/data-reporting-formats#16s-amplicon-sequencing) is designed to make the microbiome profiles of ESS samples more Findable, Accessible, Interoperable, and Reusable ([FAIR](https://www.go-fair.org/fair-principles/)). As outlined below, the standard provides file formats, vocabulary, and metadata requirements for uploading two key amplicon data products to the repository: taxon tables and representative sequence files.

## Scope of the Amplicon Data Reporting Format
The amplicon reporting format only collects metadata at the level of the taxon table and its representative sequences. This table is sometimes called the exact sequence variant (ESV) or amplicon sequence variant (ASV) or, more broadly, operational taxonomic unit (OTU) table. The standard does not store all the information associated with raw sequencing (for example, sequence barcodes). Metadata about the conditions in which each sample was collected and stored should be included with the [Sample Metadata](https://github.com/ess-dive-community/essdive-sample-id-metadata).

After collection, samples may be subjected to more than one strategy for nucleotide recovery and sequencing and to more than one strategy for generating taxon tables. Therefore, each taxon table submitted to ESS-DIVE should have both sequencing and bioinformatic metadata recorded in the metadata files described below. To the extent possible, metadata fields are defined to match those outlined in the Minimum Information about any Sequence ([MIxS](https://www.gensc.org/pages/standards-intro.html)) standards. This standard is already used for sequencing data uploaded to the [Earth Microbiome Project](https://earthmicrobiome.org/protocols-and-standards/metadata-guide/) and the [National Center for Biotechnology Information’s Sequence Read Archive](https://www.ncbi.nlm.nih.gov/sra/docs/submitmeta/).

## How to contribute to the Amplicon Data Reporting Format
Guidelines and templates for this reporting format were developed by ESS-DIVE community partners with input from microbiome researchers. The templates presented below represent an initial effort that will be refined with user input. If you would like to suggest a change to the reporting format, please submit a GitHub issue using one of the templates we provide [here](https://github.com/ess-dive-community/essdive-amplicon/issues/new/choose). If you have questions about the reporting format, you can email ESS-DIVE support at ess-dive-support [at] lbl.gov.  

## Licensing information
The repository content is licensed for use under the [CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/)

## Funding and acknowledgements
Funding for the development of the ESS-DIVE Amplicon Data Reporting Format was provided by the U.S. Department of Energy, Office of Science, Office of Biological and Environmental Research, Climate and Environmental Science Division, Data Management program.

## Recommended citation
Weisenhorn, P., Beilsmith, K. (2022). ESS-DIVE Reporting Format for Amplicon Abundance Tables. Environmental System Science Data Infrastructure for a Virtual Ecosystem (ESS-DIVE), ESS-DIVE repository. https://doi.org/10.15485/1865729

## Related references
Vangay, P. et al. Microbiome metadata standards: report of the national microbiome data collaborative’s workshop and follow-on activities. Msystems 6.1, e01194-20. (2021). doi: https://doi.org/10.1128/mSystems.01194-20
 
Yilmaz, P. et al. Minimum information about a marker gene sequence (MIMARKS) and minimum information about any (x) sequence (MIxS) specifications. Nat. Biotechnol. 29, 536 415–420 (2011). doi: https://doi.org/10.1038/nbt.1823
 
Earth Microbiome Project. https://earthmicrobiome.org/protocols-and-standards/metadata-guide/ (2022).
 
National Center for Biotechnology Information. SRA Metadata and Submission Overview. https://www.ncbi.nlm.nih.gov/sra/docs/submitmeta/ (2019).
