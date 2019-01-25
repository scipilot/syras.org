![logo](/assets/images/SYRAS-logo-thin-small.png "SYRAS")

# SYRAS - A Systematic Review Assistant

SYRAS is an online reference screening tool, aimed at assisting the process of reviewing thousands of articles during a systematic review. 

Where does SYRAS fit into the wider review process?

A typical workflow scenario might be summarised as follows:

1. Journal database article search (sourcing articles by keyword, reference/citations)
2. **Systematic Review Process (filtering thousands down to dozens)**
3. Data extraction (of experimental methods, results/statistics)
4. Meta-analysis and/or further research.

SYRAS will help you with Step 2. It allows you to import from journal database searches in common formats (RIS, PubMed) and merge and deduplicate the resulting reference sets into a unified library. You can then quickly screen the references by title and abstracts (alone or in a team of reviewers) flagging the articles which are relevent to your study. Once you have a settled on the subset of relevent references, you may export this list to another RIS or PubMed file, for import into Endnote or other document management system to purchase the articles. You can return to SYRAS later and add further references and repeat the process or modify your choices - supporting a wide variety of workflows.

## Overview of Features

1. Screening and classification of article references
2. Import/export popular reference database formats
3. De-duplication of references
4. Team collaboration tools: email invites, blinding, access controls, comments.
5. Systematic Review workflow tools: 
  * Review phases,
  * Split reference library into sub-sets, 
  * Randomisation and workload distribution,
  * Classification disagreements review
6. Assistance: keyword highlighting, document classification prediction, keyboard shortcuts
7. Personal data management and privacy controls

[Screenshots](screenshots.md)

## How to get SYRAS

There are two ways to use SYRAS, depending on your budget and technical skills.

1. Supported: you can purchase access to an online application for individual or teams at syras.org. 
Contact `syras-info @ scipilot . org` with your requirements to discuss options.
2. DIY: SYRAS is open source and therefore freely available for you to install and manage your own instance of the application.

Details

If you simply want access to an online app, the SYRAS creators at scipilot.org can provide a supported instance, with pricing depending on the scale of your project requirements. Factors include the size of the team of collaborators, how many article references you expect to be importing and how long you will need access to the dataset. It's common for formal reviews to run slowly for months or even years, so maintaining a paid plan for this period needs discussing (for example the account could be exported and shutdown during long periods of inactivity).


If funds are not available, but you or your organisation has IT skills you can set up your own web hosting and install the software via Docker, Amazone ECS or manually. There is documentation at https://github.com/scipilot/sysrev-assist-docker. The Docker installation is fully automated and works well on a Docker host such as Digital Ocean one-click app, including a automated setup and renewal of web security certificates via Let's Encrypt. The Amazon AWS ECS installation option is more hands-on and still being fine-tuned.

