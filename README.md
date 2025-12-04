## Metadata (schema.org Dataset)

The following JSON-LD block provides structured metadata for this curated dataset
using the schema.org `Dataset` type:

```jsonld
{
  "@context": "https://schema.org/",
  "@type": "Dataset",
  "name": "Chicago Food Inspections — Cleaned & Curated Dataset",
  "description": "A curated version of the City of Chicago Food Inspections dataset used to analyze and model predictors of food inspection outcomes in Chicago.",
  "url": "https://github.com/Jennie0205/CS598",
  "creator": {
    "@type": "Person",
    "name": "Jennie Yang"
  },
  "publisher": {
    "@type": "Organization",
    "name": "University of Illinois at Urbana-Champaign"
  },
  "license": "https://www.chicago.gov/city/en/narr/foia/open_data_portal_terms_of_use.html",
  "keywords": [
    "food inspections",
    "public health",
    "Chicago",
    "open data",
    "predictive modeling",
    "data curation"
  ],
  "distribution": [
    {
      "@type": "DataDownload",
      "encodingFormat": "text/csv",
      "contentUrl": "https://data.cityofchicago.org/resource/4ijn-s7e5.csv",
      "name": "City of Chicago Food Inspections (raw open data)"
    }
  ],
  "variableMeasured": [
    "inspection_id",
    "dba_name",
    "aka_name",
    "license_",
    "facility_type",
    "risk",
    "address",
    "city",
    "state",
    "zip",
    "inspection_date",
    "inspection_type",
    "results",
    "violations",
    "latitude",
    "longitude",
    "location",
    "failed",
    "year",
    "month",
    "day_of_week"
  ]
}

