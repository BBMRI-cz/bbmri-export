# bbmri-export
## Patient information
| Attribute | Attribute Format  
| --- | --- 
| patient_id | integer
| birth_date | ISO_8601
| sex | male/female/unknown
| status | alive/deceased/unknown
| consent | boolean
| consent_sign_date | ISO_8601
| consent_retraction_date | ISO_8601
| country_of_residence| ISO_3166-3


## Specimen information
- There are 5 tipes of specimen
  - Tissue, Serum, Genome, DiagnosisMaterial, Blood

### Elements of each specimen

#### Shared elements
- SampleID
- BiopsyID
- PredictiveID
- TakingDate
- Diagnosis (ICD-10)
- Retrieved (preop, op, postop, unknown)

#### Specific additional elements for Tissue
- MaterialType
- TNM (TNM-7)
- pTNM (TNM-7)
- Topography (ICD-O-3)
- morphology (ICD-O-3)
- grading
- cutTime
- freezeTime
