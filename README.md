# Introduction

## What Is UniChem?

UniChem is a very simple, large-scale non-redundant database of pointers between chemical structures and EMBL-EBI chemistry resources. It is designed to allow researchers to easily query multiple source data sets for a given chemical identifier or structure. Within UniChem, molecules from different sources are considered identical if they share the same Standard InChI. 

Primarily, this service has been designed to maintain cross references between EBI chemistry resources. These include primary chemistry resources \(ChEMBL and ChEBI\), and other resources where the main focus is not small molecules, but which may nevertheless contain some small molecule information \(eg: Gene Expression Atlas, PDBe\).

Its purpose is to optimize the efficiency with which structure-based hyperlinks may be built and maintained between chemistry-based resources, and is particularly suitable for creating such links 'on the fly' \(by use of REST web services\). 

The advantage of UniChem is that it implements an easily scalable and maintainable system of chemical structure integration within the EBI-Search infrastructure, allowing future new chemistry resources within the EBI to be included with minimal effort. Interestingly, centralised mapping for external resources such as PubChem, ZINC, etc is also straightforward and economical, and provides a wider cross-referencing service. The recent exposure of UniChem externally to EMBL-EBI provides these same mapping benefits to resources outside of EMBL. Recent open access papers listed on the [citation page](https://www.ebi.ac.uk/unichem/info/citation) describe further background.

Downloading of data from source databases, and the uploading and registration into UniChem is highly automated. Because the configuration and resources of different source databases vary widely, it is necessary to employ a variety of data downloading procedures \(such as ftp, web services, oracle calls, etc\). The downloading procedures adopted for each source are summarized on the summary page for each source, accessed via the [sources](https://www.ebi.ac.uk/unichem/ucquery/listSources) page. Since some data is unsuitable for use in UniChem, or may damage the data integrity within the database, a series of rules are automatically applied when loading data. These rules are summarized on the [Rules for Loading](https://www.ebi.ac.uk/unichem/info/rulesforloading) page.

## Terms of Use

[http://www.ebi.ac.uk/about/terms-of-use/](http://www.ebi.ac.uk/about/terms-of-use/)

