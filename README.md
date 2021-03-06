## Data Generation Toolkit

<img src="https://raw.githubusercontent.com/SFDO-Community-Sprints/DataGenerationToolkit/master/Assets/DataGenerationLogoFinal051320.png" width="300" alt="Data Generation Toolkit Logo featuring Astro in a rain of data" style="float:right" >

This project aims to create toolkit of tools and documentation for generating test data sets based on admin-selected criteria.

### Project Name

Data Generation Tool

Major use cases for these data sets include:

- QA an org populated with permutations of all, or nearly all, the types of data that are relavent to the project.
- Be able to reliably and easily load sample data into a given Salesforce org (production, sandbox or scratch).
- Have a data set for demos, potentially with the ability to add specific sets of data that could be used for story based training materials.
- Have a data set that ensures the privacy of people represented in the dataset (ie not real names)
- Have data sets at scales that allow for testing bulk data processing.

### Project Vision/Goals

- Everyone has access to an open process/tool to reliably generate sample data for telling user stories
- Admin-friendly interface to define requirements for the data generated
- Data sets generated through this process could be appopriate for medium-sized orgs and can fit in a sandbox
- Data sets generated through this process could be valid for large data valume (LDV) testing
- Develop process for how you can build test data sets that follow a story (automated? manual? best practice doc?)
- Prioritize leadership development/capacity building through project leadership/contributions from customers, partners, devs, etc

### Ongoing Projects

Currently the project team has two major efforts for our work:

- Documentation of existing tools and partial solutions
- Creation of a community supported tool that will empower easy creation of data sets tailored to an org's needs.
- Sample Recipes for Salesforce.org packages.

### Project Meetings

The main project team meets monthly to maintain momentum between sprints. You can contact us through the [PowerOfUs Hub](https://powerofus.force.com/s/group/0F91E000000brOoSAI/community-project-data-generation) to get details for joining those meetings. Notes from project meetings are recorded on the [wiki for this repository](https://github.com/SFDO-Community-Sprints/DataGenerationToolkit/wiki).

## Project Theme

- theme-community-ecosystem

## Project Vertical

_Everyone._

This project is aimed at helping ease the process of generating test data for projects. Nearly all Salesforce projects benefit from improving this process.

To help people identify with specific audiences while creating documentation we have created a series of [project personas](https://raw.githubusercontent.com/SFDO-Community-Sprints/DataGenerationToolkit/master/Assets/DataGenPersonas_202102.pdf) that we speak to and about in our materials. This is not a complete picture of everyone who will benefit, but it helps us focus our efforts and may help you understand us.

### Current Project Team

Help us give you the thanks you deserve and ensure future contributors know who to contact if they have questions! Please ensure that all contributing members of the team are included.

- Team Leader(s):
  - Aaron Crosman (Attain)
  - Samantha Shain (William Penn Foundation)
  - Cassie Supilowski (OneGoal)

### Project Team Accomplishments

- [Between Sept '20 Virtual Sprint and Feb '21 Virtual Sprint]
  - Completed first full draft of Data Generation Guide document; including technical edit
  - Kicked the tires on Snowfakery, for real
  - Made several public presentations
  - Implemented Project Boards to track issues and discussion topics
  - Survived despite pandemic, fascism, etc.
- [9/23-9/24 Virtual Sprint]
  - Drafted architecture diagrams for a UI to sit on top of Snowfakery. This will be called _Snowmakery!_ There are two proof of concepts that have been initiated. One is inside of the org, the other is in Heroku.
  - Analyzed survey data from 75 community members; updated relevant Personas based on survey insights
  - Established document outline and Admin Story for documentation project that describes how to Generate Data and Move Data between orgs
  - Documented limitations and considerations for Partial Data sampling algorithm and manual steps, third party apps, and code for creating mock data records
  - Documented steps for an Admin-audience to use CCI to move data records from one Dev Sandbox to another Dev Sandbox (or any two persistent orgs)
  - QA-ed documentation steps for CCI steps (referenced above)
- [3/31 -> 4/1 virtual sprint]
  - Determined that Snowfakery accomplishes many of the original requirements brainstormed at the Philly Sprint (fall 2019) (namely: ability to generate mock data with related tables, random names and values, standard and custom objects, datasets of any size/scale, ability to populate Salesforce orgs)
  - Socialized Snowfakery to community members
  - Onboarded project leadership from multiple orgs and began application for inclusion in Open Source Commons program
  - Refined use cases and differentiated Snowfakery from (1) existing tools in the market (2) proprietary tools at Salesforce (3) Full Sandbox product
  - Brainstormed 2+ potential directions for extending Snowfakery to include an admin-friendly web interface
  - Reviewed documentation and install steps
  - Overhauled ReadMe file

#### Proof of Concept Code

During the course of this project some ideas have been tested in code, and to ensure that code isn't lost and doesn't confuse other efforts in this repo they are kept in the proofs-of-concept directory.

Currently those include:

1. [A CumulusCI Task](proofs-of-concept/OriginalCciTask) created during this project's first sprint to generate permutations of data.
1. [A web-based Snowfakery recipe editor](proofs-of-concept/SnowmakeryEditory) created during the fall 2020 virtual sprint. This was the second tool named Snowmakery and largely confirmed that this project's UI will bare that name.

### Past Project Team Members

| Full Name             | Github Username                                     | Sprint(s)                                          |
| --------------------- | --------------------------------------------------- | -------------------------------------------------- |
| Fatama Ahmed          | [ffarag85](https://github.com/ffarag85)             | 2019 Philly Sprint                                 |
| Michael Beaty         | [mbeaty-sf](https://github.com/mbeaty-sf)           | Virtual Mar. 2020, Virtual Sept. 2020              |
| Andrew Beyer          |                                                     | Virtual Sept. 2020                                 |
| Joe Blodgett          |                                                     | Virtual Sept. 2020                                 |
| Francisco Borges      | [ciscoborges](https://github.com/ciscoborges)       | 2019 Philly Sprint                                 |
| Chris Chen            | [chrisVCH](https://github.com/chrisVCH)             | Virtual Mar. 2020                                  |
| Rebecca Cole Sullivan | [rcolesullivan](https://github.com/rcolesullivan)   | Virtual Mar. 2020                                  |
| Aaron Crosman         | [acrosman](https://github.com/acrosman)             | 2019 Philly, Virtual Mar. 2020, Virtual Sept. 2020 |
| Andrew Curran         | [andrew-curran](https://github.com/andrew-curran)   | 2019 Philly Sprint                                 |
| Marciana Davis        | [mdportfolio](https://github.com/mdportfolio)       | Virtual Sept. 2020                                 |
| Debbie Duran          |                                                     | Virtual Sept. 2020                                 |
| Michael Kolodner      | [mkolodner](https://github.com/mkolodner)           | 2019 Philly, Virtual Mar. 2020, Virtual Sept. 2020 |
| Jason Lantz           | [jlantz](https://github.com/jlantz)                 | 2019 Philly, Virtual Mar. 2020                     |
| Allison Letts         | [allisonletts](https://github.com/allisonletts)     | 2019 Philly, Virtual Mar. 2020                     |
| Jung Mun              | [eehjunggnujhee](https://github.com/eehjunggnujhee) | Virtual Sept. 2020                                 |
| Lawrence Newcombe     | [LawrenceLoz](https://github.com/LawrenceLoz)       | Virtual Sept. 2020                                 |
| Paul Prescod          | [prescod](https://github.com/prescod)               | Virtual Mar. 2020, Virtual Sept. 2020              |
| David Reed            | [davidmreed](https://github.com/davidmreed)         | 2019 Philly, Virtual Mar. 2020                     |
| Erin Schroder         | [eschroder](https://github.com/eschroder)           | Virtual Mar. 2020                                  |
| Samantha Shain        | [samanthashain](https://github.com/samanthashain)   | Virtual Mar. 2020, Virtual Sept. 2020              |
| Kim Snipes            | [kimsnipes](https://github.com/kimsnipes)           | 2019 Philly Sprint                                 |
| Cassie Supilowski     | [csupilow](https://github.com/csupilow)             | Virtual Mar. 2020, Virtual Sept. 2020              |
| Amanda Styles         | [demanda](https://github.com/demanda)               | Virtual Mar. 2020                                  |
| Tyler Woebkenberg     | [tylerw-sfdc](https://github.com/tylerw-sfdc)       | Virtual Mar. 2020                                  |

## Useful References

- [Project Meeting Notes](https://github.com/SFDO-Community-Sprints/DataGenerationToolkit/wiki).
- [Snowfakery](https://github.com/SFDO-Tooling/Snowfakery)
  - [Main Docs](https://snowfakery.readthedocs.io/en/docs/)
  - [Paul's SF Architechs blog on snowfakery](https://medium.com/salesforce-architects/generate-realistic-datasets-with-snowfakery-5349225b033d)
  - [Snowfakery SF Examples](https://github.com/SFDO-Tooling/Snowfakery/tree/master/examples)
  - [Aaron’s Noodling on a recipe editor (not currently functional)](https://github.com/acrosman/snowmakery)
  - [Aarons blog post about generating NPSP Data](https://spinningcode.org/2020/11/generate-sample-data-for-salesforce-npsp/)
  - [Samantha's Blog post about using Snowfakery](https://thedataarealright.blog/2021/01/15/snowfakery-till-you-makery/)
- [Fellow Developers, What Should Our Last Name Be?](https://dev.to/roygreenfeld/fellow-developers-what-should-our-last-name-be-cle)
- [Data Management with CumulusCI Trailhead](https://trailhead.salesforce.com/en/content/learn/modules/data-management-with-cumulusci?trail_id=build-applications-with-cumulusci)
- [Data Generation Toolkit project on Power of Us Hub](https://powerofus.force.com/s/group/0F91E000000brOoSAI/community-project-data-generation)
- [Smart Sandbox](https://www.smartsandbox.com/index.html): their website is still up but no longer active
- [Faker Documentation](https://faker.readthedocs.io/en/master/)
- [NPSP Data Dictionary](https://attain-projects.quip.com/yD1wAsdz1m1Q/NPSP-Public-Data-Dictionary)
- [Wave Data Generator](https://github.com/ttse-sfdc/sfdc-wave-data-generator) (generates data for Salesforce org, and builds linkages between objects)
- [JSON/YAML Editor](https://json-editor.github.io/json-editor/)
