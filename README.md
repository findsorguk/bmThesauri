British Museum thesauri
================================================

These thesauri have been extracted from the collection.britishmuseum.org sparql endpoint, where they exist in SKOS format.
I wanted an easy way to look at the entire set in one go, they are intended to allow easy co-referencing of the PAS structure with the BM's for CIDOC-CRM mapping.

Each file's basic structure presents:

1. The URI (subject from skos:concept) where skos:inScheme
2. The preferred label (skos:prefLabel)
3. The scope note (skos:scopeNote)

Several files contain more information such as places, which holds alternate names with the URI repeated for each.

I'll publish the full sparql queries to extract these when the endpoint I used goes to production.

--------

Some queries are here:
https://github.com/findsorguk/BritishMuseumSparql

bmPerson-institution-better.tsv.gz is produced by person-institution.sh using these "split-queries":
* person-institution-1-namesGenderNote.rq
* person-institution-2-profession.rq
* person-institution-3-nationality.rq
* person-institution-4-birth.rq
* person-institution-5-death.rq

It has a lot more data: url name otherNames  type gender profession nationality birth death note 