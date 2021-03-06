# SARS-CoV-2 Contextual Data Specification - Collection template and associated materials for SARS-CoV-2 metadata

## Overview
The Public Health Alliance for Genomic Epidemiology ([PHA4GE](https://pha4ge.org)) is a global coalition that is 
actively working to establish consensus standards, document and share best practices, improve the availability of 
critical bioinformatic tools and resources, and advocate for greater openness, interoperability, accessibility and 
reproducibility in public health microbial bioinformatics. 

In the face of the current SARS-CoV-2 pandemic, [PHA4GE](https://pha4ge.org) has identified a clear and present need 
for a fit-for-purpose, open source SARS-CoV-2 contextual data standard. As such, we have developed an extension to the 
[INSDC](http://www.insdc.org/) pathogen package, providing a SARS-CoV-2 contextual data specification based on 
harmonisable, publicly available, community standards.


## SARS-CoV-2 metadata specification
Public health genomics contextual data includes sample metadata, lab/clinical/epidemiological data, and methods 
information. Contextual data enables the interpretation of the sequence data, informs decision making for public health 
responses, and facilitates scientific understanding of infectious disease. 

Contextual data that are structured and consistent can be more easily understood and processed by both humans and 
computers, and can be more easily aggregated and reused for different types of analyses. Therefore, this specification 
is implementable via a contextual data template package: containing collection template, reference guide, controlled 
vocabulary and mapping to existing standards, as well as an array of protocols and tools to support the harmonisation and 
submission of sequence data and contextual information to public repositories. The specification and all of the 
supporting materials are freely available in this repository.


## Content description

**Table 1:** Resources that form the PHA4GE SARS-CoV-2 contextual data specification package available  in this repository.
| File Name 	| Resource 	| Description 	|  	|
|-	|-	|-	|-	|
| PHA4GE SARS-CoV-2 Contextual Data Template 2.1.xlsx 	| Collection template and controlled vocabulary pick lists 	| Spreadsheet-based collection form containing different fields (identifiers and accessions, sample collection and processing, sequencing, host information, host exposure information, bioinformatics and QC metrics, author acknowledgements). Fields are colour-coded to indicate required, recommended or optional status. Many fields offer pick lists of controlled vocabulary. Vocabulary lists are also available in a separate tab. 	|  	|
| PHA4GE SARS-CoV-2 Contextual Data Template 2.1.xlsx	| Reference guide 	| Field definitions, guidance, and examples are provided as a separate tab in the collection template .xlsx file. 	|  	|
| PHA4GE Contextual Data SOP 1.0.docx 	| Collection template SOP 	| Step-by-step instructions for using the collection template are provided in the SOP. Ethical, practical, and privacy considerations are also discussed. Examples and instructions for structuring sample descriptions as well as sourcing additional standardized terms (outside those provided in pick lists) are also discussed. 	|  	|
|  	| PHA4GE fields to metadata standards mapping 	| PHA4GE fields are mapped to existing metadata standards such as the Sample Application Standard, MIxS 5.0, and the MIGS Virus Host-associated attribute package. Mappings are available in the Reference guide tab. Mappings highlight which fields of these standards are considered useful for SARS-CoV-2 public health surveillance and investigations, and which fields are considered not applicable. 	|  	|
| PHA4GE to Sequence Repository Field Mappings 1.0.xlsx 	| ENA, NCBI and GISAID submission requirements to PHA4GE field mappings 	| Many PHA4GE fields have been sourced from public repository submission requirements. The different repositories have different requirements and field names. Repository submission fields have been mapped to PHA4GE fields to demonstrate equivalencies and divergences. 	|  	|
|  	| Data submission protocol (NCBI) 	| The SARS-CoV-2 submission protocol for NCBI provides step-by-step instructions and recommendations aimed at improving interoperability and consistency of submitted data. 	|  	|
|  	| Data submission protocol (ENA) 	| The SARS-CoV-2 submission protocol for ENA provides step-by-step instructions and recommendations aimed at improving interoperability and consistency of submitted data. 	|  	|
|  	| Data submission protocol (GISAID) 	| The SARS-CoV-2 submission protocol for GISAID provides step-by-step instructions and recommendations aimed at improving interoperability and consistency of submitted data. 	|  	|
| PHA4GE_SARS-CoV-2_Contextual_Data_Schema.json 	| JSON structure of PHA4GE specification 	| A JSON structure of the PHA4GE specification has been provided for easier integration into software applications. 	|  	|

### Collection template and controlled vocabulary pick lists
The PHA4GE SARS-CoV-2 Contextual data Collection Template can be used for data management, and consists a 
spreadsheet-based (.xlsx) collection template, a reference guide, and a controlled vocabulary list. This information 
does not have to be shared, but sharing with public repositories is encouraged when permitted. 

Fields are grouped according to whether they describe sampling, host information (symptoms, exposures etc), sequencing, 
bioinformatics and quality control metrics, etc. The collection template contains "required" (colour-coded yellow), 
"strongly recommended" (colour-coded purple) and "optional" (colour-coded white) fields. In many fields, picklists of 
ontology-mapped controlled vocabulary are offered to better standardize data values. 

### Reference guide
To facilitate the use of the collection template, a reference guide with field definitions, further 
guidance/instructions, and examples of structured data is available.

### Collection template SOP
A Standard Operating Procedure (SOP) containing instructions for using the collection template. 

The template SOP provides users with step-by-step instructions for populating the template, looking up standardized 
terms, and how best to structure sample descriptions. The SOP also highlights a number of ethical, practical, and 
privacy considerations for data sharing.

### PHA4GE fields to metadata standards mapping TODO
Mapping of the The PHA4GE SARS-CoV-2 Contextual data Collection Template fields to standards and public repository 
submission requirements (NCBI, ENA and GISAID). 


### ENA, NCBI and GISAID submission requirements to PHA4GE field mappings
Mapping of the The PHA4GE SARS-CoV-2 Contextual data Collection Template fields to standards and public repository 
submission requirements (NCBI, ENA and GISAID).

### Data submission protocol (NCBI)

### Data submission protocol (ENA) 

### Data submission protocol (GISAID)

### JSON structure of PHA4GE specification
The versioned specification contextual data collection template in machine-amenable JSON format. Due to JSON format 
limitation, it deviates slightly from the collection template where the "required" (colour-coded yellow) fields are 
set as required and both the "strongly recommended" (colour-coded purple) and "optional" (colour-coded white) fields 
are both set as option. 

The JSON is produced automatically from the csv version of the template using the [this]() script.

**Table 2** Terms for SARS-CoV-2 submission template according to the PHA4GE contextual data collection specification  
| Column 	| Description 	|
|:-:	|:-:	|
| Interface Label 	| Column headers in the submission template 	|
| Required/Optional 	| Type of requirement according to PHA4GE's template specification. Limited to the values "Optional", "Recommended" and "Required".  	|
| Definition 	| Short description for the expected interface label value. 	|
| Value Type 	| Expected interface label's value type. Limited to "String", "Int" and "Float". 	|
| Example 	| Example for the expected interface label value. 	|
| Guidance 	| Detailed description for the expected interface label value. 	|

## Contacts 
For more information and/or assistance, contact `datastructures@pha4ge.org` or the issue page of this repository.


