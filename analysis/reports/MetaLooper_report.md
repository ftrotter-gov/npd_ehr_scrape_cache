# Meta Tag Analysis Summary

## What This Analysis Does
This analysis examines the "meta" tag structure in FHIR JSON files. It tracks the 
presence of meta tags and their expected subfields (versionId, lastUpdated, source) 
while also identifying any unknown keys that appear beyond the expected ones.

- **Expected Fields:** versionId, lastUpdated, source
- **Categories:** Has meta, no meta, individual subfield presence
- **Special Feature:** Reports unknown meta keys beyond expected ones
- **Examples:** Longest/shortest/random by filename length

## Processing Results
**Files Processed:** 383487
**Files Failed:** 0
**Total Meta Categories:** 5

## Meta Tag Distribution

| Meta Category | Count | Longest Example | Shortest Example | Random Example |
|---------------|-------|-----------------|------------------|----------------|
| No Meta Tag | 290539 | [entry_Organization_1811435a7ea-7a1b883e-e0f0-4cb2-b938-4b6fd8d60f0c.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/abeo_solutions_inc_87133ed24a4073af176beaf74cd27a1e/organization/entry_Organization_1811435a7ea-7a1b883e-e0f0-4cb2-b938-4b6fd8d60f0c.json) | [entry_Organization_001.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/1life_healthcare_inc_b8bf6b68b0098021b1122dda499a9ab0/organization/entry_Organization_001.json) | [entry_Organization_1811435a7ea-7a1b883e-e0f0-4cb2-b938-4b6fd8d60f0c.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/abeo_solutions_inc_87133ed24a4073af176beaf74cd27a1e/organization/entry_Organization_1811435a7ea-7a1b883e-e0f0-4cb2-b938-4b6fd8d60f0c.json) |
| Has Meta Tag | 92948 | [entry_Endpoint_142519.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/azalea_health_431baf9cf4a84b1f9865df363dcd5e35/endpoint/entry_Endpoint_142519.json) | [entry_Endpoint_135243.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/azalea_health_431baf9cf4a84b1f9865df363dcd5e35/endpoint/entry_Endpoint_135243.json) | [entry_Endpoint_142082.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/azalea_health_431baf9cf4a84b1f9865df363dcd5e35/endpoint/entry_Endpoint_142082.json) |
| Has lastUpdated | 87087 | [entry_Endpoint_142519.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/azalea_health_431baf9cf4a84b1f9865df363dcd5e35/endpoint/entry_Endpoint_142519.json) | [entry_Endpoint_135243.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/azalea_health_431baf9cf4a84b1f9865df363dcd5e35/endpoint/entry_Endpoint_135243.json) | [entry_Endpoint_137985.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/azalea_health_431baf9cf4a84b1f9865df363dcd5e35/endpoint/entry_Endpoint_137985.json) |
| Has versionId | 1248 | [entry_Endpoint_143bc7c9-010a-4864-aedf-ecc31a53cff4.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/azalea_health_ab5783b7bda76708800d03e01f6405c3/endpoint/entry_Endpoint_143bc7c9-010a-4864-aedf-ecc31a53cff4.json) | [entry_Endpoint_6295a912-4865-4d03-a903-9763e02910c5.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/azalea_health_ab5783b7bda76708800d03e01f6405c3/endpoint/entry_Endpoint_6295a912-4865-4d03-a903-9763e02910c5.json) | [entry_Endpoint_3bc6717e-0b49-499a-a827-9c297914ea0c.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/azalea_health_ab5783b7bda76708800d03e01f6405c3/endpoint/entry_Endpoint_3bc6717e-0b49-499a-a827-9c297914ea0c.json) |
| Has source | 664 | [entry_Endpoint_1.100028.21.2.191.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/eyefinity_inc_7f49a3ffd9754854012a649ba6df4325/endpoint/entry_Endpoint_1.100028.21.2.191.json) | [entry_Organization_67.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/doctome_inc_1c145d17bd33da1368482c0b50afe0e6/organization/entry_Organization_67.json) | [entry_Organization_111.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/doctome_inc_1c145d17bd33da1368482c0b50afe0e6/organization/entry_Organization_111.json) |

**Total Files Analyzed:** 383487

## Unknown Meta Keys Found

The following meta keys were found beyond versionId, lastUpdated, and source:

* `profile`
* `tag`
