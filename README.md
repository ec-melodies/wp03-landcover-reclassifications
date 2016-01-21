Reclassification definitions for some land cover category sets in JSON-LD

melodies_modis.jsonld describes a mapping from the MELODIES WP3 Land Cover to the MODIS Land Cover categories. The mapping embeds the MODIS Land Cover category details (like label and preferred colour) for convenience in software applications such that this document can be used stand-alone to apply such a mapping. 

These mappings are included as DCAT datasets in [WP3.jsonld](https://github.com/ec-melodies/wp02-dcat/blob/master/WP3.jsonld#L64). The JSON-LD file has a content type of `application/ld+json;profile="http://purl.org/voc/cpm_catremap"`. The fictional profile URI shall restrict the structure of the JSON-LD file to be exactly as it is in the melodies_modis.jsonld and other files.
