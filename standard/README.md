# OGC CDB Volume 13

## Content

This folder contains the text for the extension

* cdb-vector-data-in-gpkg.adoc - the main extension document with references to all sections
* remaining adocs - each section of the standard document is in a separate document: follow directions in each document to populate
* figures - figures go here
* images - Image files for graphics go here. Image files for figures go in the "figures" directory. Only place in here images not used in figures (e.g., as parts of tables, as logos, etc.)
* requirements - directory for requirements and requirement classes to be referenced in clause_7_normative_text.adoc
* code - sample code to accompany the standard, if desired
* abstract_tests - the Abstract Test Suite comprising one test for every requirement, optional
* UML - UML diagrams, if applicable

At regular intervals, conversions of all the .adoc documents to html and pdf will be made.

## Building

To produce the HTML of the standard run `asciidoctor --safe -a data-uri -o
cdb-vector-data-in-gpkg.html cdb-vector-data-in-gpkg.adoc`.

To produce the PDF of the standard run `asciidoctor-pdf --safe -o
cdb-vector-data-in-gpkg.pdf cdb-vector-data-in-gpkg.adoc`
