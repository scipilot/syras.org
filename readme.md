
[Home](/) | [Screenshots](/screenshots) | [Contact](/contact.html) | [Release History](/releases) | 

**SYRAS is an online reference screening tool, aimed at assisting the process of reviewing and classifying thousands of article abstracts during a systematic review.**

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

There are three ways to use SYRAS, depending on your budget and technical skills.

1. Beta programme: you can join the beta programme and use the application now, if you are willing to help finalise the software.

2. DIY (self hosted): SYRAS is open source and therefore freely available for you to install and manage your own instance of the application.

3. Once the system has been put through its paces in the beta programme, syras.org will host an easy to use online version with support and assistance.
You will be able to purchase access to the online application for individual or teams at syras.org.  
<a href="/contact.html">Click here contact us<a/> to register interest and discuss your requirements.

### Beta programme details
As the software is still in "beta" (product testing and evaluation), there are pilot trials running which you may join for no cost. 

The latest version of SYRAS is currently hosted on a small-scale limited access platform which is fully functional but not professionally supported. 

Please contact us if you want to get involved in trialling the beta software and helping to improve and finalise it.
 <a href="/contact.html">Click here contact syras.org<a/>.

### DIY (self hosted) details

If funding is not available but you or your organisation have IT skills, you can set up your own instance of the web application on your own hosting provider and install and manage the software and database yourself.

It can be run via containers in Docker or Amazon AWS ECS, or manually as a "MEAN stack" application. The [Docker installation](https://github.com/scipilot/sysrev-assist-docker) is fully automated and works well on a Docker host such as Digital Ocean's one-click app, including automated setup and renewal of web security certificates via Let's Encrypt. An Amazon AWS ECS installation option is also being developed.

### Paid Application details (future)

If you simply want access to an online app, the SYRAS creators at scipilot.org can provide a supported instance, with pricing depending on the scale of your project requirements. Factors include the size of your team of collaborators, how many article references you expect to be importing and how long you will need access to the data. As reviews may run intermittently over months or even years, maintaining a monthly paid plan for the entire duration may not be suitable. Therefore import/export features may be required to shutdown the project during long periods of inactivity.

## About the developers

SYRAS was originally developed by a collaboration between Pip Jones of [Scipilot.org](https://scipilot.org) and Dr Nic Badcock and other researchers from [Macquarie University](https://mq.edu.au), migrating a MATLAB product to online.

More history can be found on the [scipilot.org development blog](http://scipilot.org/blog/2018/04/13/introducing-systematic-review-assistant/).

SYRAS is the second major product developed by Scipilot, after [MOTIf](https://motif.org.au) which provides online test resources 
primarily to assist diagnosing reading and learning difficulties in children. The MOTIf application has been running online for over 10 years, 
and we are proud to have helped tens of thousands of children across Australia and the wider world. 
I would hope SYRAS could become as popular and helpful.


# Future Directions

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

Please <a href="/contact.html">click here to contact us<a/> for more information on the further development of SYRAS.


---

![logo](/assets/images/SYRAS-logo-thin-small.png "SYRAS")
