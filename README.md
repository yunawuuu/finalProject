# Final Project
This repository will be where you complete your final project for the class Big Data and Economics. 

## Steps to get started:
1. Fork this repository.
2. Make sure this repository is private by navigating to `Settings` and changing it to Private under the **Danger Zone**
3. Add me (kgcsport) as a collaborator by going to `Settings` > `Collaborators and teams`. 
4. Clone your repository to your personal computer, so you can get to work on it over time.
5. Create folders for `code`, `data`, `writing`, `literature`, or any others that feel relevant. Turn in the project proposal, literature review, data analysis, and final written project, as well as their associated `*tex.` or `.Rmd` code in the `writing` folder. 
6. Add files to your `.gitignore` like `*.csv`, `*.dta`, `*.tsv` that I have not added. 
7. Start developing your project.

# README (insert a title here)
*Use this space to create a README for the project so that I (or someone else) could happen upon this repository and understand:
1. What is the project about?
2. How is the project structured?
3. How do I replicate the project? 

# Scoresheet
This project will have several iterative deadlines below:
| Category / Description                            | Due Date         | Points Earned | Points Possible |
|---------------------------------------------------|--------------|---------------|-----------------|
| **Project Proposal** (about one page)           | 9/24             |               |                 |
| Clearly stated question                           |              |               | 5               |
| Identified potential data sources                 |              |               | 5               |
| _Subtotal_                                          |              |               | 10              |
| **Literature Review**                                |  10/22            |               |                 |
| At least five references in the bibliography (use a .bib file) |              |               | 2.5             |
| Properly include in-text citations (easier with [LaTeX](https://www.overleaf.com/learn/latex/Bibliography_management_with_bibtex) or [Rmarkdown](https://bookdown.org/fmcron/Rhodes-template/bibliographies.html))  |              |               | 2.5             |
| Organized by method/finding not chronologically   |              |               | 5               |
| _Subtotal_                                          |              |               | 10              |
| **Data Description**                               |     11/17         |               |                 |
| Clear, concise summary of dataset (source, basic)  |              |               | 5               |
| Visualization of key feature in data              |              |               | 5               |
| _Subtotal_                                          |              |               | 10              |
|**Peer Review**                                       |    12/1          |               |                 |
| Constructive feedback                                 |              |               | 5               |
| Potentially suggest new code                         |              |               | 5               |
| _Subtotal_                                          |              |               | 10              |
| **Methods**                                        |  12/11 (with paper)     |               |                 |
| At least 1 properly formatted equation             |              |               | 5               |
| Appropriate econometric or data science technique for the question |              |               | 10              |
| _Subtotal_                                          |              |               | 15              |
| **Findings**                                       |  12/11 (with paper)      |               |                 |
| At least 1 table and 1 graphical visualization     |              |               | 5               |
| Clear, concise explanation of data                 |              |               | 10              |
| _Subtotal_                                          |              |               | 15              |
| **Code to reproduce results**                     |  12/11 (with paper)      |               |                 |
| README file with directions on how to replicate... |              |               | 10              |
| Automated compilation of figures / tables / ot... |              |               | 5               |
| Exhibits good programming practices               |              |               | 2.5             |
| Thoughtfully organized                            |              |               | 2.5             |
| _Subtotal_                                          |              |               | 20              |
|**Written Report**                                   |    12/11          |               |                 |
| 5-10 pages (excluding References, Tables, and Figures) |              |               | 5               |
| Compiled in LaTeX or Rmarkdown                    |              |               | 5               |
| Contains 6 sections: intro, lit rev, data, methods, findings, conclusion |              |               | 5               |
| Source code of report (.Rmd or .tex) included with other code |              |               | 5               |
| _Subtotal_                                          |              |               | 20              |
| **Grand total**                                       |              |               | 100             |

## Project Proposal
This should be one page at most. The key thing is to identify a research question you want to ask and potential data sources you have in mind. If you have a key method to apply in mind or a paper you want to build off of -- even better! 

## Literature Review
This should walk through critical literature related to your topic. These should be scholarly sources or data science sources (depending on the research question). 

The literature review should be in an essay format. You should talk about what other scholarly work has been done on the question you are answering. 

### Goals of literature review

Here are goals summarized from a guide by [Duke University](https://econ.duke.edu/sites/econ.duke.edu/files/documents/Writing%20Literature%20Reviews.pdf.

1. Critically analyze the body of work on a question
  - Identify strengths and weaknesses of past work
  - Concisely highlight the most important things to know about other work -- *Note: You decide what think is most important to highlight.*
2. Put your project in context of the literature
  - Is your paper one of the first one a topic?
  - One of a ton?
  - Is it the first empirical paper on a topic that is otherwise answered using theory?
3. Highlight your contribution
  - Richer data than before?
  - New estimation technique?
  - New question that has never been answered before?
4. Establish scholarly credentials
  - Shows you did your homework
  - You know the lit and where you are adding

### Organization

1. Begin with comments on the body of research as a whole.
  - Start broad and narrow in. Assess the big picture of the literature.
2. Organize your review according to a theme (data, methodology, results, etc.)
  - You should organize your literature review by **theme** rather than date. A theme could be the data used, the methodology, or the results. Something that links together the disparate work that helps a reader make sense of what is known and where scholars disagree. 
3. Start paragraphs with explicit context sentence. What part of the theme are we talking about here? Datasets? Methods?
4. Highlight merits and shortcomings of existing studies.
5. Highlight how your study contributes.

#### Citation style: APA, Chicago, JEL, etc. (I'm not picky, just pick one and stick to it.)

#### What not to do:
1. Explain every study you cite in full detail
2. Give general statements about the literature like "Scholars think XYZ." Cite explicitly.
  
## Data Description
This should clearly describe the data:
- Where did it come from?
- How could I access it?
- Summary of key features of the data

## Possible datasets to use:
This list is also not exhaustive. Not all datasets you can find below are big, but they are publicly available. If you come up with a good project that can be done with big data that's not accessible, one of the datasets below might substitute for this course. I will penalize you for needing data that you cannot access. In fact, I will reward you for being creative to see what you can still learn with what is publicly available. 

### General
- [kaggle](https://www.kaggle.com/datasets)
- Bates guide by [Christine Murray]( https://libguides.bates.edu/ECON368).
- [TidyTuesday data](https://github.com/rfordatascience/tidytuesday)

### Government
- [Data.gov](https://data.gov/)
- [NOAA](https://www.ncdc.noaa.gov/cdo-web/datasets) atmosphere data
- [OpenFEMA](https://www.fema.gov/about/reports-and-data/openfema)
- [Center for Medicaid and Medicare Services](https://data.cms.gov/)
- [NYC OpenData](https://opendata.cityofnewyork.us/data/), [LA Open Data](https://data.lacity.org/), etc.
- [FEC Campaign Finance Data](https://www.fec.gov/data/browse-data/)
- [National Archives](https://www.archives.gov/open/available-datasets.html)
- [FOIA Data Set Downloads](https://www.foia.gov/foia-dataset-download.html)
  
### Research-related
- [J-Pal Catalog of Administrative Datasets](https://www.povertyactionlab.org/catalog-administrative-data-sets)
- [Opportunity Insights Data](https://www.povertyactionlab.org/catalog-administrative-data-sets)
- [Recommender System and Personalization Datsets](https://cseweb.ucsd.edu/~jmcauley/datasets.html)
- [NBER Public Use Data](https://www.nber.org/research/data?page=1&perPage=50)
- [NonProfit Open Data Collective](https://github.com/orgs/Nonprofit-Open-Data-Collective/repositories)

### Journalism
- [ProPublica Data "store"](https://www.propublica.org/datastore/datasets)
- [ProPublica Data APIs](https://www.propublica.org/datastore/apis)
- [FiveThirtyEight data archive](https://github.com/fivethirtyeight) -- especially the [Uber TLC Foil](https://github.com/fivethirtyeight/uber-tlc-foil-response)

### Social Media
- [Data for Good](https://dataforgood.facebook.com/) by Facebook
- [Amazon AWS Open Data Source Project](https://aws.amazon.com/marketplace/pp/prodview-zxtb4t54iqjmy?sr=0-1&ref_=beagle&applicationId=AWSMPContessa)
- [FOMC Historical Transcripts](https://www.federalreserve.gov/monetarypolicy/fomc_historical.htm)
- [Twitter Datasets](https://github.com/shaypal5/awesome-twitter-data)

and much, much more.

## Methods
Tell me what empirical method you are using, how it addresses the question, and what potential flaws with this method are. For example, if you use difference-in-difference design, tell me about the parallel trends assumption and what it means in your setting. 

## Findings
Briefly describe the results in your paper. Say the key finding and show it visually (if you can make a graph) or with a well-formatted table. 

## Conclusion
Tell me what you told me and potential directions for future research. 

## Written Report
Put all of the above together.

## Code
I am evaluating on how the code works. I should be able to run it on my computer.
