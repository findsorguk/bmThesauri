British Museum thesauri
================================================

These thesauri have been extracted from the collection.britishmuseum.org sparql endpoint, where they exist in SKOS format.
I wanted an easy way to look at the entire set in one go, they are intended to allow easy co-referencing of the PAS structure with the BM's for CIDOC-CRM mapping.

Each file's basic structure presents:
1) The URI (subject from skos:concept) where skos:inScheme
2) The preferred label (skos:prefLabel)
3) The scope note (skos:scopeNote)

Several files contain more information such as places, which holds alternate names with the URI repeated for each.

I'll publish the full sparql queries to extract these when the endpoint I used goes to production.