[![](https://img.shields.io/badge/Cortex-Integrations-ff6600)](https://www.cortex-ia.com/cortex-integrations/) 
[![](https://img.shields.io/badge/LinkedIn-Cortex-blue.svg?logo=linkedin)](https://www.linkedin.com/company/cortex-intelligent-automation-software/)
[![](https://img.shields.io/badge/Blog-Cortex-a0c326)](https://www.cortex-ia.com/latest-news-at-cortex/)

# CTX-CHK-PEP-CIA
This project contains a subtask that can be used to to validate if a person is a Politically Exposed Person (PEP). This is a common tasks performed by onboarding new clients, employees, accounts etc.
This specific subtask will check a name against the CIA Foreign Governments website (which is updated on a weekly basis) [https://www.cia.gov/resources/world-leaders/](https://www.cia.gov/resources/world-leaders/ "https://www.cia.gov/resources/world-leaders/")


## Inputs
The subtask accepts the following inputs:
- **i_name_to_locate**: supply a person's name (just the name, no titles etc) to search for
- **i_name_to_locate**: and optionally a country or government can be supplied (i.e. "Netherlands" for "The Netherlands"). If this is not supplied all countries/governments will be checked (which obviously takes much more processing time)

## Outputs
The subtask provides the following output:
- **o_person_details**: a structure with the results of the search. There is always an element called **found**. This element can have a value of "yes" or "no". If yes 3 additional elements will be part of the structure: **person_name**, **person_country**, **person_position**

# Installation Instructions
Download the Studio Package file and Import it into your Cortex Environment.
Don't forget to apply rights using the Studio Authorization module.

:thumbsup: Enjoy! :wink:
