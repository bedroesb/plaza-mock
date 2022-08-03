---
title: News
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

# News

**Public release PLAZA 5.0** (2021-09-13)

PLAZA 5.0 is the latest iteration of the PLAZA framework consisting of two instances: Dicots 5.0 and Monocots 5.0. The total number of species across both instances is now 134, a near-doubling from the 71 species integrated in PLAZA 4.0.  
  
New features include

*   New and improved visualizations for functional enrichment and genome mapping
*   An updated REST API
*   BED import tools for the workbench
*   ... and lots of small improvements/fixes

  
If you notice bugs or issues, feel free to contact us.

Posted by Michiel Van Bel

**Preliminary release PLAZA Monocots 4.5** (2019-07-10)

This intermediate update of the PLAZA platform, with a focus on the Monocots, became necessary due to substantial annotation updates to species present in the 4.0 PLAZA instances. For example, the latest wheat release (IWGSCv1.1) is a big step up from the version in Monocots 4.0 (TGACv1.0). Furthermore, the genomes for some other important crop species have also become available in the meantime, necessitating an update to the PLAZA platform.

Posted by Michiel Van Bel

**Best instance selection** (2019-01-07)

We have implemented a new tool to find the best PLAZA instance for your species of interest. This tool is available from the PLAZA portal page, and will give an overview of all the PLAZA instances containing your species of interest, together with the various assembly and annotation versions.

Posted by Michiel Van Bel

**Data Warehouse API** (2018-10-13)

We have integrated a global PLAZA API system which will query all public PLAZA instances, and return the FTP data storage for each PLAZA instance.  
  
For more information, visit the [documentation](https://bioinformatics.psb.ugent.be/plaza_development/documentation/data_warehouse).

Posted by Michiel Van Bel

**PLAZA 4.0 release notes** (2017-09-01)

PLAZA 4.0 is the latest iteration of the PLAZA framework consisting of two instances: Dicots 4.0 and Monocots 4.0. The total number of species across both instances nearly doubled from 37 species in PLAZA 3.0 to 71 species in PLAZA 4.0, with a much broader coverage of crop species (e.g. wheat, palm oil) and species of evolutionary interest (e.g. spruce, Marchantia).  
  
New features include

*   New and improved visualizations for multiple sequence alignments, phylogenetic trees (PhyD3) and gene collinearity (interactive WGDotplot & SyntenyPlot)
*   An Interactive Phylogenetic Module allowing users to create custom phylogenetic trees by using the PLAZA platform as reference
*   Access by an application programming interface (API) through a RESTful web service
*   Improved management of Workbench experiments between different users

  
If you notice bugs or issues, feel free to contact us.

Posted by Michiel Van Bel

**Move from http to https** (2017-08-01)

Due to security concerns all PLAZA instances will now automatically make use of the secure http protocol (https).

Posted by Michiel Van Bel

**Conserved TF binding sites added to PLAZA Dicots 3.0** (2016-06-01)

Based on our recent paper ['A Collection of Conserved Non-Coding Sequences to Study Gene Regulation in Flowering Plants' (Van de Velde et al., 2016)](http://www.plantphysiol.org/content/early/2016/06/03/pp.16.00821.abstrac), PLAZA Dicots 3.0 now hosts conserved transcription factor (TF) binding site information for >600 TFs. Apart from identifying for any TF target genes with a conserved binding site in ten different species, also the associated gene families and Gene Ontology/InterPro annotations can be browsed. Reversely, for every gene the conserved TF binding sites in the upstream/intron/downstream non-coding can also be retrieved.  
The TF binding sites are available for the following species: _Arabidopsis thaliana_, _Brassica rapa_, _Populus trichocarpa_, _Glycine max_, _Prunus persica_, _Cucumis melo_, _Eucalyptus grandis_, _Vitis vinifera_, _Solanum lycopersicum_, _Solanum tuberosum_  
  
For more examples, please see our tutorial [Browsing conserved TF binding sites](http://bioinformatics.psb.ugent.be/plaza/documentation/conserved_binding_sites_tutorial).

Posted by Klaas Vandepoele

**PLAZA 3.0: bug fix BHI orthology** (2016-03-01)

Dear PLAZA users,  
  
we want to inform you that we identified and corrected a software bug in one of the tools used in PLAZA 3.0 to compute integrative orthology.  
Specifically, for the Best-Hits-and-Inparalogs (BHI) method, we found that while the Best Hits in other species were correctly scored, inparalogs were not correctly identified. This means that no genes were incorrectly identified as being orthologous, but that some orthologs might have been missed (no false positives, some false negatives).  
  
This issue has now been resolved and the data in he PLAZA 3.0 Dicots and Monocots databases and the corresponding FTP download sections have been updated.  
  
Apologies for any inconvenience caused, The PLAZA team

Posted by Michiel Van Bel

**Update PLAZA 3.0 Monocots integrative orthology** (2016-06-26)

We want to inform you that the PLAZA 3.0 Monocots website has been updated, now including additional integrative orthology information for _Oryza sativa_ (osa). Downstream data types, incl. orthology-based GO projection as well as the functional annotations for Monocots 3.0 Workbench experiments, have also been updated.

Posted by Klaas Vandepoele

**Thank you for participating in the PLAZA survey.** (2013-03-19)

We would like to express our gratitude to everyone who participated in the PLAZA survey. If you have any more questions or remarks, you can send them plaza@psb.vib-ugent.be

Posted by Michiel Van Bel

**View all colinear gene pairs** (2012-08-14)

We have added a new feature on the Gene page to rapidly explore all colinear gene information across species. See the function 'View all colinear gene pairs' or check this [example](http://bioinformatics.psb.ugent.be/plaza/genes/colinear_gene_pairs/AT3G14320)!

Posted by Klaas Vandepoele

**PLAZA 3.0 roadmap** (2012-04-07)

The PLAZA team is currently working towards the 3.0 release of the PLAZA platform and we're looking for user input! What new genomes and features would you like to see incorporated? Are there any other improvements that you would like to see? Contact us at [plaza@psb.ugent.be](mailto:plaza@psb.ugent.be).

Posted by Michiel Van Bel

**PLAZA is tip of the week on openhelix** (2011-12-01)

From openhelix.org:  
  
"Plaza, a resource for plant comparative genomics, has a lot more than meets the eye at first. Currently the database has comparative tools and data for nearly 2 dozen plants including monocots, dicots, mosses and algae..."  
  
Read more and view the video on [Openhelix](http://blog.openhelix.eu/?p=9664)

Posted by Michiel Van Bel

**PLAZA 2.5 online** (2011-09-10)

The third release of the PLAZA platform, designated version 2.5, is currently available. New genomes include strawberry (Fragaria) and cacao (Theobroma) while several other species, like _Arabidopsis thaliana, Zea mays_ and _Brachypodium distachyon_, have been updated.  
  
The current release includes >900,000 genes from 25 species, yielding 22,350 multi-species gene families.  
  
New tools include the Circle Plot, a multi-species WGDotplot, a Gene Family Finder, Expansion Plot, and an Integrative Orthology Viewer to explore orthologous genes in other species by combining different orthology prediction methods.  
  
Workbench experiments from PLAZA 2.0 can be transferred to PLAZA 2.5.

Posted by Michiel Van Bel

**Detection orthologous genes** (2010-12-01)

Through the integration of a complementary set of data types orthologous gene relationships are inferred. The rationale of combining multiple approaches is to generate a consensus view of gene orthology between different species.  
  
This new tool can be accessed via the Gene page and Workbench.

Posted by Michiel Van Bel

**Public Release PLAZA 2.0** (2010-09-01)

The second release of the PLAZA platform integrates structural and functional annotation from 23 plants covering 11 dicots, 5 monocots, 2 (club-)mosses and 5 algae (>840,000 genes). Eighty-seven percent of all protein-coding genes are stored in 32,332 multi-gene families (70% covering homologs from multiple species). Users who would like to continue working with PLAZA 1.0, please check the section Archive in the menu bar.  
  
Disclaimer: bulk downloads are currently disabled, please use the Workbench for high-throughput sequence retrieval.

Posted by Michiel Van Bel

**Plant Cell Publication** (2010-02-05)

The PLAZA paper has been published in Plant Cell (issue December 2009).  
  
For more details check [http://www.plantcell.org/cgi/content/abstract/21/12/3718](http://www.plantcell.org/cgi/content/abstract/21/12/3718)

Posted by Sebastian Proost

**Update Workbench functions** (2009-11-10)

New features:

*   Increased the number of workbench experiments per user from 10 to 30
*   Advanced gene selection functionality: convert gene subsets (based on GO, InterPro, species or gene family) into a new workbench experiment
*   Update GO enrichment statistics

  
Other suggestions? Do not hesitate to [contact us](http://bioinformatics.psb.ugent.be/plaza/pages/credits)!

Posted by Michiel Van Bel

**Genome Browser AnnoJ** (2009-08-30)

AnnoJ has been integrated as PLAZA's Genome Browser. Currently all gene models together with a DNA sequence track are available.

Posted by Klaas Vandepoele

**Workbench activated** (2009-08-12)

We have developed a Workbench where for user-defined gene sets different genome statistics can be calculated. For genes sets saved by the user detailed information about functional annotations, associated gene families, block and tandem gene duplicates, and gene structure is provided. The GO enrichment tool makes it possible to determine if a user-defined gene set is over-represented for one or more GO terms. Please check the Help >> Tutorial section for more details.

Posted by Michiel Van Bel

**Tutorials** (2009-05-01)

Several tutorials have been added to show how the different functions of the PLAZA platform can be accessed.  
The introduction covers some basics like how to find genes you're interested in. The other tutorials cover more complex topics : Gene family evolution, Genome evolution, Functional annotation and PLAZA's Workbench.  
  
The tutorials can be found [here](https://bioinformatics.psb.ugent.be/knowledge/wiki-plaza/tutorial).

Posted by Sebastian Proost

//<!\[CDATA\[ document.mybaseurl='/plaza/'; //\]\]>
