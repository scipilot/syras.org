
SYRAS is an online reference screening tool, aimed at assisting the process of reviewing thousands of articles during a systematic review. 

Where does SYRAS fit into the wider review process?

A typical workflow scenario might be summarised as follows: SYRAS will help you with Step 2. 

1. Journal database article search (sourcing articles by keyword, reference/citations)
2. **Systematic Review Process (filtering thousands down to dozens)**
3. Data extraction (of experimental methods, results/statistics)
4. Meta-analysis and/or further research.

SYRAS enables you to import from journal database searches in common formats (RIS, PubMed, EndNote) and merge and deduplicate the resulting reference sets into a unified library. You can then quickly screen the references by title and abstracts (alone or in a team of reviewers) flagging the articles which are relevent to your study. Once you have a settled on the subset of relevent references, you may export this list to another RIS or PubMed file, for import into Endnote or other document management system to purchase the articles. You can return to SYRAS later and add further references and repeat the process or modify your choices - supporting a wide variety of workflows.

## Overview of Features

1. Screening and classification of article references
2. Import/export popular reference database formats
3. De-duplication of references
4. Team collaboration tools: email invites, blinding, access controls, comments.
5. Systematic Review workflow tools: 
  * Review phases,
  * Split reference library into sub-sets, 
  * Randomisation and screening workload division,
  * Classification disagreements review
6. Screening Assistance: 
  * visual keyword highlighting, 
  * keyboard shortcuts, 
  * document classification prediction (see below)
7. Personal data management and simple privacy controls

## Screenshots
[Click here to see some screenshots of the app in action](screenshots.md)

## How to get SYRAS?

There are two ways to use SYRAS, depending on your budget and technical skills.

1. Supported (cloud hosted): you can purchase access to an online application for individual or teams at syras.org. 
Contact `syras-info @ scipilot .org` with your requirements to discuss options.
2. DIY (self hosted): SYRAS is open source and therefore freely available for you to install and manage your own instance of the application.

Details

If you simply want access to an online app, the SYRAS creators at scipilot.org can provide a supported instance, with pricing depending on the scale of your project requirements. Factors include the size of your team of collaborators, how many article references you expect to be importing and how long you will need access to the data. As reviews may run intermittently over months or even years, maintaining a monthly paid plan for the entire duration may not be suitable. Therefore import/export features may be required to shutdown the project during long periods of inactivity.


If funding is not available but you or your organisation have IT skills, you can set up your own web application hosting and install the software via Docker, Amazon ECS or even manually. The [Docker installation](https://github.com/scipilot/sysrev-assist-docker) is fully automated and works well on a Docker host such as Digital Ocean's one-click app, including automated setup and renewal of web security certificates via Let's Encrypt. An Amazon AWS ECS installation option is also being developed.

The software is still in "beta", so there are a number of pilot trials already running. Please contact us if you want to get involved.


## Research into Automating Systematic Reviews using AI

When SYRAS was originally created, the goal was to automate the tedious process of reviewing thousands of references 
while selecting their relevance to a particular topic of study.

A machine-learning algorithm was developed in 2017 which could be trained by a researcher using SYRAS over a perhaps 200 hundred sample classifications.
This algorithm was found to be able to predict the classification of the remaining corpus of thousands of articles, up to around 85% accuracy. 
While this is not perfect it was found to be a closer match than two human researchers would agree on the same set of references.

This algorithm is available for demo use in SYRAS now in the form of the "Article Relevance Prediction (Machine Learning) v1." presentation assistant.

However, to be used within a formal review process it would need to be scientifically validated and it's role in the workflow better defined. As such it is not currently being offered fully to "finish the job" as originally intended.

We are looking for collaborators to help us progressing this goal. What would be useful to us:
* access to project data to train the algorithm (i.e. using your classifications and article references)
* anyone interested in helping to validate the algorithm variants (e.g. PhD)
* anyone interested in piloting the "full" model of an AI performing the review (e.g. a parallel blind review by the AI, or using it as a "Turing Collaborator")
* anyone interested in coding or machine learning (software development)
* or any other ideas!

Please contact us at `syras-info @ scipilot .org` for more information.

---

![logo](/assets/images/SYRAS-logo-thin-small.png "SYRAS")
