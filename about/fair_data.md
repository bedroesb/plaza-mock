---
title: FAIR Data
first-nav: /about/
second-nav:
    - title: Contact
      url: /about/
    - title: Credits
      url: /about/credits/
    - title: FAIR Data
      url: /about/fair_data/
    - title: GDPR
      url: /about/GDPR/
    - title: Licensing
      url: /about/licensing/
    - title: News
      url: /about/news/
    - title: Publications
      url: /about/publications/
    - title: Terms of service
      url: /about/terms_of_service/
---

# PLAZA & FAIR Data


## What is FAIR data?

FAIR data is data that adheres to certain guiding principles, in order make it possible for data providers to easily:

*   Find data and data sources
*   Access data and data sources
*   Interoperate between data providers
*   Reuse data

These principles are further [clarified and standardized](https://www.go-fair.org/fair-principles/) by the FAIR working groups

## How is PLAZA FAIR?

The developers of the PLAZA platform are dedicated to make the PLAZA platform compatible with the FAIR guiding principles.  
This is a long-term goal for the PLAZA project, and with each software iteration we are one step closer to being fully FAIR compliant.

### Findability

The data is findable: we currently offer a warehouse service which provides, for versions 3.0 and later, JSON objects detailing where the data is located. This service works both per PLAZA instance, and globally by aggregating the data for all PLAZA instances.

1.  (meta)Data are assigned a globally unique and eternally persistent identifier.  
    Work in progress, once all dependencies have been identified. The current JSON objects are uniquely identified through the URL they are coming from.
2.  Data are described with rich metadata.  
    Current JSON objects have the necessary meta-data within them, and additional documentation is available.
3.  (meta)Data are registered or indexed in a searchable resource.  
    Work in progress within the ELIXIR framework.
4.  Metadata specify the data identifier.  
    Data identifiers are logically build and constructed from meta-data core principle terms.

### Accessibility

The data is accessible. Both the PLAZA warehouse and PLAZA gene-centric rest API function through the standard HTTP(s) protocol, make use of standard JSON formats to exchange data, etc.

1.  (meta)Data are retrievable by their identifier using a standardized communications protocol.  
    Yes.
2.  The protocol is open, free, and universally implementable.  
    Yes.
3.  The protocol allows for an authentication and authorization procedure, where necessary.  
    Yes.
4.  Metadata are accessible, even when the data are no longer available.  
    For the warehouse data: the JSON objects (meta-data) describing and listing the data (on the FTP servers) will continue to be available as long as the PLAZA instance(s) are available, even if the data on the FTP servers is no longer available.

### Interoperability

1.  (meta)Data use a formal, accessible, shared, and broadly applicable language for knowledge representation.  
    Currently the meta-data is not yet formalized fully, but there is work in progress to further make use of ontologies to optimize this.
2.  (meta)Data use vocabularies that follow FAIR principles.  
    By making use of standard ontologies this will indeed be the case.
3.  (meta)Data include qualified references to other (meta)data.  
    Work in progress.

### Reusability

The goal of the PLAZA warehouse is to provide the PLAZA data to other frameworks (e.g. Galaxy) in order to speed up the deployment of new tools/data within those frameworks. The meta-data is standardized over all PLAZA instances in order for the service to be reusable for other frameworks.

1.  (meta)Data have a plurality of accurate and relevant attributes.  
    Implemented. By making use of accurate and relevant meta-data, the requested data is quickly identified. Furthermore, each data file contains the necessary attributes to identify the content per file.
2.  (meta)Data are released with a clear and accessible data usage license.  
    [View the PLAZA data license.](/plaza/pages/data_license)
3.  (meta)Data are associated with their provenance.  
    We provide the data per PLAZA instance, and within each PLAZA instance we keep track of the genome versions that are used to produce the data. Furthermore, we intend to track additional information such as used software versions, dates/versions of external files (e.g. OBO files for Gene Ontology etc. ) in order to increase the provenance.
4.  (meta)Data meet domain-relevant community standards.  
    All implemented. The data is offered in the standard formats expected by the community (e.g. FASTA for sequence files, GFF for annotation files, TAB-delimited for other data files). Meta-data exchange is through JSON.

## More information

Additional information about FAIR data can be found here:

*   [GO-FAIR website](https://www.go-fair.org/fair-principles/)
*   [FORCE11 website](https://www.force11.org/group/fairgroup/fairprinciples)
