# UCL NHS Power Apps Connector

This project is a part of the University College London MSc Computer Science summer project in collaboration with NHS and Microsoft. This repository contains two Power Connectors and a demonstration Power App that leverages these connectors.

## Contents

- **Power Connectors**: Located in the `PowerConnector` folders. These folders contain swagger files that can be directly uploaded to the Power Platform Custom Connector options without needing authentication.
- **Demonstration Power App**: Find this in the `PowerApps` folder. It showcases a solution built for the NHS crisis mental health service, utilizing the power connectors developed in this project.

### APIs

The connectors are based on the APIs found in the following links:

- [Organisation Data Service FHIR](https://digital.nhs.uk/developer/api-catalogue/organisation-data-service-fhir)
- [Personal Demographics Service FHIR](https://digital.nhs.uk/developer/api-catalogue/personal-demographics-service-fhir)

## Getting Started

### Power Connectors

Navigate to the `PowerConnector` folders to find the swagger files. Upload them directly to the Power Platform Custom Connector options (no authentication required).

### Demonstration Power App

1. Go to the `PowerApps` folder.
2. Find the zip file and upload it directly to Power Apps using the 'Import Canvas App' option.
3. Allow the Office 365 Outlook connector to access your acount as email sender.
4. To ensure the app functions correctly, select data on the left bar, add the configured power connectors. Rename the power connectors to "ODS_FHIR_API" and "PDS_FHIR_API".

## Contact

For any inquiries or further information, feel free to reach out at:

- Email: [ucabcda@ucl.ac.uk](mailto:ucabcda@ucl.ac.uk)
