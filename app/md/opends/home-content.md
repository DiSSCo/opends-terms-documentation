Open Digital Specimen (openDS) is a comprehensive data specification that describes the essence of a "Digital Specimen" as implemented by [DiSSCo](https://www.dissco.eu/), a digital surrogate of a specimen on the internet with its related information. 
The openDS data model documented here is based on the draft [GBIF Unified Model](https://www.gbif.org/composition/HjlTr705BctcnaZkcjRJq/gbif-new-data-model) as well as biodiversity information standards like [Darwin Core](https://www.tdwg.org/standards/) and [ABCD](https://www.tdwg.org/standards/abcd/). 
openDS is designed to enhance [FAIR aspects](https://www.go-fair.org/fair-principles/) of specimen data including support for provenance data and machine actionability.  
For each digital object we created a terms, guide and resources page.
In the top right you will find a navigation bar where there are dropdowns for each type of documentation we provide.

Getting started[](#getting-started)
-----------------------------------
*   [Normative Term List Digital Specimen](digital-specimen-terms)
*   [Quick Reference Guide Digital Specimen](digital-specimen-guide)
*   [Json Schema](https://schemas.dissco.tech) provide the original schemas on which this site is generated
*   The [openDS Github](https://github.com/DiSSCo/openDS) provides any additional information available, including examples.
*   For questions and change requests please create a [Github Issue](https://github.com/DiSSCo/openDS/issues/new/choose)

SSSOM data standard mappings can be in the Resource Page for three international standards:
- [Darwin Core Archive](https://schemas.dissco.tech/schemas/data-mapping/0.4.0/sssom_dwca.tsv)  
- [Access to Biological Collection Data (ABCD) + Extension for Geosciences (EFG)](https://schemas.dissco.tech/schemas/data-mapping/0.4.0/sssom_abcdefg.tsv)  
- [Darwin Core Data Package](https://schemas.dissco.tech/schemas/data-mapping/0.4.0/dwc_dp.tsv)  

For more information on the data model see the Living Data 2025 Presentation given at 22-10-2025.  
[Living Data 2025 Presentation](https://drive.google.com/file/d/17HZCCLf8EMwTolmwkaLIBRJQieuOmTBq/view?usp=drive_link)

-------------
## Latest Updates

Media has been updated to version 0.5.0 to include media derivatives.  
These media derivatives are derived from the original item and will not get their own object.  
Instead they will be nested in the media digital object.  
First use case for the media derivatives will be the generation of thumbnail images.

