# Payload Type Analysis Summary

## What This Analysis Does
This analysis examines payloadType fields in FHIR JSON files, including their coding 
subkeys and address classification. It analyzes system/code values under coding subkeys, 
classifies address subkey contents using regex patterns, and tracks header subkey presence.

- **Coding Analysis:** System and code statistics from coding subkey
- **Address Classification:** Uses regex classification on address subkey contents
- **Header Detection:** Tracks presence of header subkey
- **Categories:** Has payloadType, coding, address, header presence
- **Examples:** Longest/shortest/random by filename length

## Processing Results
**Files Processed:** 383487
**Files Failed:** 0

## Payload Type Presence

| Category | Count | Longest Example | Shortest Example | Random Example |
|----------|-------|-----------------|------------------|----------------|
| Has Payload Type | 95570 | [entry_Endpoint_idFA6NjJ01p.WnqGN2lfXufQ.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/aarista_technology_llc_98dd118c306868b25684644c95fe4c75/endpoint/entry_Endpoint_idFA6NjJ01p.WnqGN2lfXufQ.json) | [entry_Endpoint_test.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/adaptamed_llc_47d439f4130f7692caea161fa0b4d2bd/endpoint/entry_Endpoint_test.json) | [entry_Endpoint_test.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/adaptamed_llc_47d439f4130f7692caea161fa0b4d2bd/endpoint/entry_Endpoint_test.json) |
| No Payload Type | 287917 | [entry_Organization_1811435a7ea-7a1b883e-e0f0-4cb2-b938-4b6fd8d60f0c.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/abeo_solutions_inc_87133ed24a4073af176beaf74cd27a1e/organization/entry_Organization_1811435a7ea-7a1b883e-e0f0-4cb2-b938-4b6fd8d60f0c.json) | [entry_Organization_001.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/1life_healthcare_inc_b8bf6b68b0098021b1122dda499a9ab0/organization/entry_Organization_001.json) | [entry_Organization_oB3nMEqxOFVmo8B.json](https://github.com/ftrotter-gov/npd_ehr_scrape_cache/blob/main/cache/fhir_json_cache/advanced_data_systems_corporation_39bf6843af633b73ecc1a2a375a3e6c8/organization/entry_Organization_oB3nMEqxOFVmo8B.json) |
| Has Coding | 51666 | N/A | N/A | N/A |

## Coding System Values

| System | Count |
|---------|-------|
| `http://ihe.net/fhir/ihe.formatcode.fhir/CodeSystem/formatcode` | 26637 |
| `http://terminology.hl7.org/CodeSystem/endpoint-payload-type` | 15915 |
| `http://hl7.org/fhir/us/davinci-pdex-plan-net/CodeSystem/EndpointPayloadTypeCS` | 6903 |
| `urn:oid:1.3.6.1.4.1.19376.1.2.3` | 1463 |
| `http://hl7.org/fhir/ValueSet/endpoint-payload-type` | 575 |
| `http://terminology.hl7.org/CodeSystem/endpoint-connection-type` | 65 |
| `http://www.acme.org.au/units` | 65 |
| `http://hl7.org/fhir/resource-types` | 41 |
| `http://terminology.hl7.org/CodeSystem/v3-HL7DocumentFormatCodes` | 9 |
| `http://hl7.org/fhir/endpoint-payload-type` | 6 |
| `'http://terminology.hl7.org/CodeSystem/endpoint-payload-type` | 5 |
| `http://ihe.net/fhir/ValueSet/IHE.FormatCode.codesystem` | 2 |
| `http://hl7.org/fhir/SearchParameter/Endpoint-payload-type` | 1 |

## Coding Code Values

| Code | Count |
|------|-------|
| `urn:hl7-org:sdwg:ccda-structuredBody:1.1` | 25652 |
| `any` | 12674 |
| `NA` | 6903 |
| `none` | 3827 |
| `urn:ihe:pcc:xphr:2007` | 2508 |
| `direct-project` | 63 |
| `Endpoint` | 13 |
| `urn:hl7-org:sdwg:ccda-structuredBody:2.1` | 10 |
| `urn:ihe:iti:xds:2017:mimeTypeSufficient` | 6 |
| `CarePlan` | 4 |
| `CapabilityStatement` | 2 |
| `hl7-fhir-rest` | 2 |
| `AllergyIntolerance` | 1 |
| `Binary` | 1 |
| `Bundle` | 1 |
| `CareTeam` | 1 |
| `Condition` | 1 |
| `Device` | 1 |
| `DiagnosticReport` | 1 |
| `DocumentReference` | 1 |
| `Encounter` | 1 |
| `Goal` | 1 |
| `Group` | 1 |
| `Immunization` | 1 |
| `Location` | 1 |
| `Medication` | 1 |
| `MedicationRequest` | 1 |
| `Observation` | 1 |
| `Organization` | 1 |
| `Patient` | 1 |
| `Practitioner` | 1 |
| `PractitionerRole` | 1 |
| `Procedure` | 1 |
| `Provenance` | 1 |
| `application/fhir+json` | 1 |
