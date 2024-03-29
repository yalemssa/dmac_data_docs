# About DMAC

A Github repository for documentation about the Beinecke Rare Book and Manuscript Library's Data Management, Analysis, and Content Unit (DMAC).

## What is DMAC

Special Collections Technical Services (SCTS) Data Management, Analysis, and Content has primary responsibility for special collections descriptive, administrative, and technical metadata for the management, discovery, and access of special collections materials. Unit works with all SCTS units to advance SCTS goals and priorities and other Beinecke and Yale special collections to advance goals and priorities. Serves as bridge to and works closely with Yale University Library Technical Services and Beinecke Library Digital Special Collections and Access to ensure SCTS alignment with and adherence to Beinecke and YUL strategies, priorities and policies. It covers three main areas: Leadership, Metadata, and Born Digital.

__Leadership__: provides vision, strategy, and policy for SCTS and Yale Special Collections data and data management systems. Is the primary product owner of YUL’s ArchivesSpace. Sponsors relevant user groups and communities of practice. Engages with and contributes to broader communities (outside Yale) building or sustaining data standards and description and management tools for special collections, e.g. ArchivesSpace, BitCurator, National Finding Aid Network (NFAN).  

__Metadata__: has primary responsibility for special collections descriptive, technical and administration data related to collections management, discovery, and access, including data management; data remediation; bulk data creation, editing, and reuse; data quality assurance and auditing; and ensuring data durability and sustainability. Provides training and creates and maintains documentation. Excludes metadata and polices governed by the YUL-TS and the Metadata Steering Committee.

__Born digital__: has primary responsibility for Beinecke Library born digital collection material. Collaborates with  other Beinecke and YUL departments to acquire, capture, stabilize, and ensure staff access to born digital content. Leads and manages the Born Digital Accessioning Support Service, which captures/images born digital collection material, creates Submission and Access Information Packages for ingest into the digital preservation system. Consults with and trains other department staff to capture and access born digital content. Provides patron access to material that is not accessible online or in Preservica. Provides training and creates and maintains documentation.

## DMAC Metadata Services

- Bulk metadata correction/remediation
- Metadata enhancement
- Migration assistance
- Processing support
- System bug/error troubleshooting
- Reporting and data analysis
- Project support
- General consultations

<!-- ## DMAC Year One Goals

### Goal 1: Create DMAC collaboratively

__Strategies / Tactics__
- Articulate and communicate a set of guiding principles for the unit
- Establish relationships and communication strategies with related units
- Recruit and onboard new staff members
- Participate in team-building exercises by using real-world projects as test cases
- Identify baseline training opportunities
- Make connections and establish new partnerships (e.g., with the Ivy Plus Libraries Confederation)

__Related BRBL Tech Services Goals__
- Goal 3: Invest in organizational wellness and team development 

__Related BRBL Strategic Goals__
- Goal 3: Strengthen stewardship capacity 
- Goal 7: Invest in organizational culture 
- Goal 8: Ensure sustainable infrastructure 	

### Goal 2: Maintain and enhance existing tools and workflows, with a focus on producing joyful automation

__Strategies / Tactics__
- Inventory existing tools/workflows, e.g., DASS tool, ArchivesSpace Export Service, ETD processing, LSF transfer tool, etc.
- Request budget that will enable foundational operations
= Institute a ticketing system for submission and prioritization of born-digital/metadata support requests
= Create a centralized Git repository for the unit

__Related BRBL Tech Services Goals__
- Goal 3: Invest in organizational wellness and team development 

__Related BRBL Strategic Goals__
- Goal 1: Focus on service to library users 
- Goal 5: Catalyze student success

### Goal 3: Approach all forms of data responsibly

__Strategies / Tactics__
- Compile list of data-remediation projects (e.g. updates required based on recent decision by the Department of Interior to change federally-designated place names that previously included the word “sq___”)
- Compile list of data-cleanup projects
- Compile list of data-enhancement projects
- Assess differences in metadata practices between BRBL and MSSA, with a view toward merging those two repositories in ArchivesSpace
- Initiate appraisal activities as part of the standard born-digital workflow

__Related BRBL Tech Services Goals__
- Goal 1: Engage in responsible stewardship practices

__Related BRBL Strategic Goals__
- Goal 2: Build collections responsibly
- Goal 4: Accelerate the creation of new knowledge

#### Goal 4: Develop a system portfolio that details departmental roles

__Strategies / Tactics__
- Define ownership roles within the Beinecke for the implementation of systems such as ArchivesSpace, BitCurator, etc.
- Identify and document system integrations

__Related BRBL Tech Services Goals__
- Goal 2: Strengthen stewardship capacity

__Related BRBL Strategic Goals__
- Goal 8: Ensure a sustainable infrastructure -->

## How to Update This Documentation

This documentation is generated by Sphinx from scripts, spreadsheets, and various .RST and .MD files within the documentation Github repository.

### Spreadsheets

The spreadsheets are stored in the `_files` directory. The spreadsheets include list of current Yale ArchivesSpace plugins, a list of current DMAC-related Github repositories, lists of completed, active, recurring, and future projects, and a list of ArchivesSpace data that is subject to data auditing protocols. 

The Github repository and plugins spreadsheets are generated via the `get_repo_data.py` script. The project and data auditing spreadsheets are created manually, and are then converted into a table by the Sphinx documentation generator.

### Github Readmes

The `get_repo_data.py` script also pulls in all READMEs from DMAC-related Github repositories, and stores them in the `readmes` directory of the documentation. 

### Other Readmes

Separate directories exist in which policy, workflow, and tutorial documentation can be added. These documents should be .MD files. 

Each directory has a corresponding .RST file in the main directory, which pulls in all of the files which are in the directories and displays them in the generated documentation.

### Building the Docs

To update the documentation, you can edit the files in the repository, and then push your changes to the dmac_data_docs Github repository. The documentation will automatically re-build. 








