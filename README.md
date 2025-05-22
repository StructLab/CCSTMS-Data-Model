> **ℹ️ Note:**  
> The **CCSTMS Model** is derived from the [Extended ERA Ontology](https://ext-era-doc.vercel.app/).


![europesRail](https://github.com/user-attachments/assets/1bdea4d1-6623-409d-bd40-17a2c865db76)


# CCS/TMS Data Model

Welcome to the **CCS/TMS Data Model Repository**! This repository serves as an extension to the Transversal CCS central resources available on [Polarion](https://polarion.rail-research.europa.eu/polarion/#/project/SPT2TS/wiki/TCCS%20SD1%20-%20Data%20Model/TCCS%20SD1%20-%20Data%20Model_INFRA) for easy accessibility and collaboration. CCS/TMS is a comprehensive, harmonized framework developed to standardize data exchange and management within the European Railway System. This data model supports the digital transformation and interoperability needs of the railway sector by providing consistent data structures for traffic control, train management, and other rail-related applications.

## Overview

The **CCS/TMS Data Model** (Control Command and Signalling/Traffic Management System) is a standardized framework aimed at enabling seamless data exchange across railway systems. Developed under the ERJU Transversal CCS, this model specifies data structures that are critical for various railway functions such as engineering, asset management, operational plan, train protection, and automated train operations. For more information, see [CCS/TMS Data Model - Scope](https://polarion.rail-research.europa.eu/polarion/#/project/SPT2TS/wiki/30%20SD1%20Deliverables/CCS_TMS%20Data%20Model%20-%20Scope%20and%20Approach%20for%20Collaboration%20and%20Specification) 

### Key Features

- **Standardized Data Language**: Establishes a consistent language for data across CCS/TMS interfaces.
- **Comprehensive Engineering and Domain Data**: Covers both Engineering Data (base data, e.g., track topology and configuration) and Domain Data (use-case-specific data tailored for system functionalities).
- **Interoperability and Scalability**: Ensures compatibility across railway systems, facilitating a scalable approach for data-driven rail operations.
- **Interface Specification**: Specific Data Model which is directly used for data & interface specification.
- **ERA Vocabulary Alignment**: Integration and full alignment with the ERA vocabulary (ontology).

- ![image](https://github.com/user-attachments/assets/4abf60b6-cce3-40c7-b983-e21b2df063fe)


## Structure of the Repository

This repository contains all necessary documentation and data model files related to the project. The structure of the folders and files within the repository is as follows:

- **Documentation**: Contains the primary project documentation for guiding users through the purpose, scope, and structure of the data models. Detailed guides, such as the *Data Model Guide*, provide an in-depth understanding of the data model’s structure, purpose, history, and development process.
- **DM Docs**: Contains documentation specific to various data model categories within the project.
- **DM Files**: Contains JSON files for each data model component, providing structured data representations.
- **Ontology**: CCSTMS RDF and TTL files representing the extended ERA vocabulary "ontology" can be found [here](https://ext-era-doc.vercel.app/).
    NOTE: Issues or questions specifically related to the extended ontology can be raised here --> [Extended ERA-Ontology]([https://github.com/StructLab/ERA-CCSTMS](https://gitlab.com/era-europa-eu/public/interoperable-data-programme/era-ontology/era-ontology/-/tree/ext-ccstms?ref_type=heads)) using appropriate tag.
- **Schemas**: Schemas in XSD and JSON formats for validating and structuring the data models.

  
## Getting Started

To get started with the CCS/TMS Data Model:

1. **Clone the Repository**: Download the repository locally to explore the data model files and documentation.
2. **Review the Documentation**: Begin with the *Introduction* document to understand the model's purpose and scope. The *Data Model Schema* and *DM Docs* provides specific details on the data structure.
3. **Explore the Model**: Use the DM Files, Ontology (RDF & TTL), and the schemas as templates for integrating this data model into your systems.

      *- Infrastructure (INFRA)*  -->    covers all infrastructure data objects <br>
      *- ATO*                     -->    configuration of ATO Trackside <br>
      *- Engineering (ENG)*       -->    Engineering of ETCS L2 <br>
      *- Map Reference (MAP)*     -->    Digital Map, e.g. for Localisation <br>
      *- Operational Plan (OPP)*  -->    used by CCS-TMS Interface Specification <br>
      *- Traffic Protection (TP)* -->    configuration for TPS / Safety Logic <br>
      *- Subset 026 (SS026)*      -->    used for Engineering of ETCS Telegrams, later also for configuration interface specification <br>
      *- Equipment model*         -->    imported from EULYNX for diagnostic purposes


## Collaboration and Development

This data model is developed in collaboration with various System Pillar domains and is continuously refined based on feedback and implementation experiences. The model integrates best practices from existing railway standards and harmonizes them for greater efficiency and functionality.

## License

This repository follows *EUPL* license agreement for authorized usage. Please refer to the [European Union Public License](https://eupl.eu/1.2/en/) for more information.

## Contributing

We welcome feedback and contributions from domain experts and end-users. If you have suggestions, encounter any issues, or need clarification, please open an issue [here](https://github.com/StructLab/CCSTMS-Data-Model/issues). Alternatively, you can also add comments directly on the relevant file/section in [Polarion](https://polarion.rail-research.europa.eu/polarion/#/project/SPT2TS/wiki/TCCS%20SD1%20-%20Data%20Model/TCCS%20SD1%20-%20Introduction%20to%20Data%20Model)

---

Thank you for visiting the CCS/TMS Data Model Repository!
