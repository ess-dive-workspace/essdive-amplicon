# ESS-DIVE Amplicon Data Reporting Format v0.1.0   

## About the Amplicon Data Reporting Forma
ESS-DIVE’s [reporting format for amplicon data](https://docs.ess-dive.lbl.gov/contributing-data/data-reporting-formats#16s-amplicon-sequencing) aims to make the microbiome profiles of ESS samples more Findable, Accessible, Interoperable, and Reusable ([FAIR](https://www.go-fair.org/fair-principles/)). As outlined below, the standard provides file formats, vocabulary, and metadata requirements for uploading two key amplicon data products to the repository: taxon tables and representative sequence files.

The data standard aims to capture the most essential sequencing and bioinformatic metadata for downstream researchers seeking to combine or compare amplicon tables and sequence sets when parameterizing models or performing meta-analyses. With this standard, ESS researchers can manage and share the abundance profiles and recovered sequences from their sample microbiomes in consistent formats. The file formats will enable seamless upload to a DOE platform for open-source data analysis, the Systems Biology Knowledgebase ([KBase](https://www.kbase.us/)).

## Scope of the Amplicon Data Reporting Format
The amplicon reporting format only collects metadata at the level of the taxon table and its representative sequences. This table is sometimes called the exact sequence variant (ESV) or amplicon sequence variant (ASV) or, more broadly, operational taxonomic unit (OTU) table. The standard does not store all the information associated with raw sequencing (for example, sequence barcodes). Metadata about the conditions in which each sample was collected and stored should be included with the [Sample Metadata](https://github.com/ess-dive-community/essdive-sample-id-metadata).

After collection, samples may be subjected to more than one strategy for nucleotide recovery and sequencing and to more than one strategy for generating taxon tables. Therefore, each taxon table submitted to ESS-DIVE should have both sequencing and bioinformatic metadata recorded in the metadata files described below. To the extent possible, metadata fields are defined to match those outlined in the Minimum Information about any Sequence ([MIxS](https://gensc.org/mixs/)) standards.

## How to contribute to the Amplicon Data Reporting Format
Guidelines and templates for this reporting format were developed by ESS-DIVE community partners with input from microbiome researchers. The templates presented below represent an initial effort that will be refined with user input. If you would like to suggest a change to the reporting format, please submit a GitHub issue using one of the templates we provide [here](https://github.com/ess-dive-community/essdive-amplicon/issues/new/choose). If you have questions about the reporting format, you can email ESS-DIVE support at ess-dive-support [at] lbl.gov.  

## Licensing information
The repository content is licensed for use under the [CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/)

## Funding and acknowledgements
Funding for the development of ESS-DIVE ESS-DIVE Amplicon Data Reporting Format was provided by the U.S. Department of Energy, Office of Science, Office of Biological and Environmental Research, Climate and Environmental Science Division, Data Management program.

## Recommended citation
Weisenhorn, Pamela; Beilsmith, Kathleen (2021): ESS-DIVE Amplicon Data Reporting Format. Environmental System Science Data Infrastructure for a Virtual Ecosystem (ESS-DIVE).

## Related references
*Will be updated soon**
