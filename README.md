## MI-Lab Exercise E04-FDM
# Registration of Research Projects and Storage in a Research Data Management System

## Local Installation
Navigate to the **Setup** folder and run `docker-compose up -d` in the terminal. This will pull all Docker images from a server. The download takes approximately 5 minutes.  
After all images have started, you can open http://localhost:3000 in your browser to access the local Local Data Hub and log in.

## Folder Structure
- `Exercise/` Contains exercise sheet, presentation slides, and solutions
- `Material/`
  -  `Dataset/` The MIMIC dataset for this exercise in CSV format
  -  `Study_documents/` The synthetic study documents to be uploaded into the research data management system  
- `Setup/` Docker Compose setup for LDH

## Study Documents
An overview of the synthetic study documents to be uploaded for the MIMIC IV Demo dataset:

| Document | Description |
|----------|----------|
| Research Data Management Plan (RDMP) | Describes how research data are created, processed, stored, and shared |
| Study Protocol | Contains the objective, design, and methodology of the study  | 
| Data Quality Rules | Standards and criteria for data quality  | 
| Data Dictionary | Structure and variables of the dataset. Facilitates interpretation of the data |  
