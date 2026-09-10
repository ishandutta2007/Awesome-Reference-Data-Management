# Awesome-Reference-Data-Management

## Top Reference Data Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Master Data Management (MDM), Reference Data, Golden Records, Data Stewardship, Multi-Domain MDM & Data Governance*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Reference Data Management (RDM)** and broader **Master Data Management (MDM)**. These systems create and maintain authoritative “golden” records for key business entities (customers, products, instruments, locations, hierarchies, etc.), manage reference data sets, enforce data quality, and distribute trusted data across the enterprise.



**Examples** include GoldenSource, NeoXam DataHub, SmartStream Reference Data Utility, RIMES, Asset Control, Informatica MDM, Ataccama ONE, Profisee, Semarchy xDM, Alveo, Reltio, TIBCO EBX, Stibo STEP, and Orchestra Networks (the category leaders).



**Open-source emphasis**: Enterprise-grade Reference Data and multi-domain MDM platforms used in capital markets and large enterprises are predominantly commercial. Open-source activity includes configurable business application platforms with strong MDM capabilities (**AtroCore**), dedicated MDM/PIM projects (**Fuyuko**, **RDataCore**), and reference implementations. This section lists every significant relevant project found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[GoldenSource](https://www.thegoldensource.com/)**  

  Established enterprise platform for enterprise data management with strong capabilities in reference data, security master, and capital-markets data domains.



- **[Reltio](https://www.reltio.com/)**  

  Cloud-native multi-domain MDM platform focused on real-time golden records, entity resolution, and connected data for customer and other domains.



- **[Informatica MDM](https://www.informatica.com/)**  

  Comprehensive master data management solution within the Informatica ecosystem, supporting multi-domain MDM, data quality, and stewardship workflows.



- **[Semarchy xDM](https://www.semarchy.com/)**  

  Intelligent data management platform combining MDM, data quality, and governance with strong matching, survivorship, and stewardship features.



- **[Profisee](https://profisee.com/)**  

  Microsoft-centric MDM platform popular for its integration with the Microsoft data stack and accessible multi-domain master data capabilities.



- **[TIBCO EBX, Stibo STEP, Ataccama ONE](https://www.tibco.com/)**  

  Enterprise platforms offering flexible data modeling, governance, product information, and master/reference data management.



- **[NeoXam DataHub, SmartStream, RIMES, Asset Control, Alveo](https://www.neoxam.com/)**  

  Specialized reference data and enterprise data management solutions frequently used in financial services and capital markets.



- **[Orchestra Networks and other RDM/MDM platforms](https://www.orchestranetworks.com/)**  

  Additional commercial tools focused on hierarchical reference data, multi-domain MDM, and regulated data domains.



## Open-Source GitHub Projects



- **[AtroCore](https://github.com/atrocore/atrocore)**  

  Open-source, highly configurable Business Application Platform with ready-made solutions for Master Data Management (MDM), Product Information Management (PIM), Digital Asset Management, and reference data scenarios. Supports golden-record modeling, validation, and distribution.



- **[Fuyuko](https://github.com/tmjeee/fuyuko)**  

  Open-source Master Data Management / Product Information Management application focused on managing product and related master data with a modern tech stack.



- **[RDataCore](https://github.com/BentBr/r_data_core)**  

  Self-hosted master data management platform built with Rust. Features a dynamic entity system, workflow engine, versioning, import/export, and API-first design for connecting multiple source systems.



- **[AURUM](https://github.com/RajaMDM/AURUM)**  

  Vendor-agnostic Master Data Management reference implementation covering the full lifecycle from raw data to golden records across multiple domains, with emphasis on data quality and stewardship patterns.



- **[open-mdm](https://github.com/open-mdm/open-mdm)**  

  Earlier open-source micro-service approach to core Hub-style Master Data Management capabilities (domain creation, dynamic schemas, adaptors, pub/sub).



- **[Other MDM & reference data projects](https://github.com/search?q=master+data+management+OR+reference+data+OR+golden+record)**  

  Community and research projects exploring entity resolution, reference data hierarchies, and stewardship workflows.



- **[PIM / product master foundations](https://github.com/search?q=PIM+OR+product+information+management+open+source)**  

  Open-source Product Information Management tools that often overlap with product-domain master and reference data use cases.



- **[Data quality & matching libraries](https://github.com/search?q=entity+resolution+OR+record+linkage+OR+data+matching)**  

  Open libraries for deduplication, matching, and survivorship that can underpin custom reference data solutions.



### Additional Strong Open-Source Options



- **Data modeling & metadata**: Open tools for defining reference data models, code lists, and hierarchies.

- **Workflow & stewardship**: BPM or low-code engines configured for data stewardship and approval processes.

- **Integration & pipelines**: Airbyte, Meltano, or custom ETL/ELT for bringing source data into an MDM hub.

- **Graph & hierarchy stores**: Open graph databases useful for complex reference data relationships and hierarchies.

- **Validation & quality rules**: Great Expectations, Soda, or custom rule engines for reference data constraints.

- Self-hosted combinations of AtroCore or RDataCore with open data-quality and integration tooling.



**Frameworks for building custom systems**:  

The strongest open-source foundations are **AtroCore** (full business application platform with native MDM), **RDataCore**, and **Fuyuko** for product-centric master data.  

These can be extended with open matching/quality libraries and integration pipelines.  

Commercial platforms (GoldenSource, Reltio, Informatica, Semarchy, Profisee, TIBCO EBX, Stibo, financial-services specialists such as NeoXam, SmartStream, RIMES, etc.) provide enterprise-scale matching, governance, industry data models, and operational reliability that most open-source assemblies still require significant effort to match.  

Many organizations use open-source tools for specific domains or prototypes while relying on commercial MDM/RDM platforms for enterprise golden-record management.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Reference and master data systems underpin critical business and regulatory processes. Data quality, auditability, access control, and change management are essential.

- Open-source MDM/RDM tools offer transparency and cost advantages but typically require more implementation effort and lack the industry-specific models, scale, and support of mature commercial platforms. Evaluate governance requirements, total cost of ownership, and operational readiness carefully.



---



**Made for data architects, master data stewards, capital-markets data teams, and enterprise information managers.**  

Let's expand open approaches to trusted reference and master data while recognizing the vital role of proven commercial platforms in large-scale, regulated environments.
