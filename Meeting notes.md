# Summary of workshop discussions
## 14-01-2022
- Discussion on the definition of scenarios.
- What metadata format can we use to describe scenarios?
- How to share scenario data without sharing licensed data?
- Ideally we make something that can be downloaded and used with one click
- Call for case-studies to work on
- Can we find funding to continue working on this topic?

## 16-02-2022
- Further discussion on the definition of scenarios. We should not reinvent the wheel, there is literature out there. However, we need to think about what kind of scenarios we would like to create.
- IAM metadata file can be a template. However, IAM uses much more variables, so the template should be simplified.
- We need to consider different levels of scenarios: economy, sectors, technology, single process. Let's start with working on economy level (multiple sectors). Afterwards we can look at how to add "satelite scenarios".
- Recipes could be used for generating scenarios. Works also for non-IAM output. We could think of a GUI of recipe: a user just moves the mouse around and the GUI creates the recipe file. A code generator.
- Scenarios can be defined in four steps: Code + scenario difference file + recipe + high-level A4 questionnaire
- We still need to look for funding. 
- A new meeting will be planned end of March/beginning of April. 

## Additional notes from participants

### FUTURA
James Joyce’s FUTURA (https://github.com/pjamesjoyce/futura) offers an interesting solution to re-producing modified databases, using “recipes”. Recipes are YAML files that describe a series of “transforming” functions (there are three types in FUTURA: altering markets, regionalization and introducing new techs) to operate to obtain a similar database.

### How to document scenarios / scenario LCI databases

- An (A4) overview / high-level description, perhaps as a question list to the scenario generator
  - This points to the detailed descriptions as well as papers etc. With detailed descriptions
  - Information on dependencies and consistencies with other scenarios
- Detailed description and data at various levels
  - Inventories that are required on top of existing LCI databases (e.g. bw Excel format or ILCD) 

### Idea for zenodo community

For the short-term, we could create a community on zenodo for LCA scenario data similar to the Industrial Ecology and Sustainability Research community (https://zenodo.org/communities/indecol/?page=1&size=20) This could ensure that data added automatically gets a DOI and zenodo allows versioning. It seems to be quite easy to create a community according to zenodo:

“Want your own community? It's easy. Just click the button to get started.
-	Curate — accept/reject what goes in your community collection.
-	Export — your community collection is automatically exported via OAI-PMH
-	Upload — get custom upload link to send to people”

So far, there is no LCA community as far as I know (at least I could not find one).

## 07-04-2022

### Presentation and discussion on premise

- new functionality: possiblilty of adding user-defined scenarios 
- several MS students are testing out this new functionality with specific case-studies
- Marc (and Carina?) will also test it out on their scenarios
- We need to think about compatibility of user-defined scenarios with IAMs and with eachother
- A graphical representation of all available scenarios and their compatibility would be nice (like a selection tree)
- We need to think about soft compatibility (is this scenario consistent with the story of the SSPS scenario) and hard compatibility (is the market I need present in the database, in what order should we apply scenarios)
- Let's reduce redundancy in documentation. If we want both a configuration file and a descriptive A4, can one of them be generated automatically based on the other?
- Ideally we could store all the created user-defined scenarios in a library so that all users can easily download them and use in their 
- We should keep in mind legal issues regarding storing/dowloading. Zenodo is not ideal. gitlab is better.


### Discussion on the future collaboration of this group
- The general feeling is that the meetings are valuable and should be continued. 
- The discussions section of this repository will be used for ongoing discussions and questions.
- At the same time, bi-monthly video-conference meetings will be organized for more in-depth discussions. Invitations will be send out. All particpipants are invited to submit agenda points.
- It may be early for a project proposal, but the idea is still in the air. Future discussions may help getting clearer ideas.
- It was suggested to look into starting a SETAC working group or a SETAC interest group. This will be on next meeting's agenda.
- Another suggestion was to organize a brightcon session.

## 23-05-2022

### Short summary
- Two objectives for database/scenario sharing were defined. The first is archiving our work and getting a DOI for referencing. A Zenodo community is a good solution for this objective. The second objective is to design a tool that combines different scenarios and creates a personalized and harmonized database for LCA practitioners. A Github repository is a good solution for creating this tool. Ideally we can integrate the two functions at some point, but first a workflow needs to be made. More detailed notes are given below.
- The presentation on consequential prospective LCA showed different methods for defining marginal suppliers and how this affects the consequential prospective market mixes. Work is ongoing to include consequential LCA in premise.
- A broader prospective LCA network was set-up during the SETAC conference. The objectives of this network include, but are not limited to exchange of research findings, clarification of terminology, exchange of data, exchange on scenario methodology, exchange on upscaling approaches.
-  A Flemish call for funding was mentioned (https://www.fwo.be/en/fellowships-funding/research-projects/sbo-projects/). However, only 20% of the funding can go to non-flemish institutions, so this is not a funding option for our working group.

### Discussion on Zenodo & Github
- A community on Zenodo allows to gather all prospective scenario data together. Each user can tag their data with the community tag, and the community curator decides whether the data belongs to the community.
- Hosting a Zenodo community would require the WG to appoint a curator. We could set up an inpersonal e-mail account for the WG for administrative purposes. This account could be shared and used as curator account to share the workload of curating and ensuring continuity of curation in case of job-changes.
- Another option is to check if Zenodo allows to share different persons to curate the community with different accounts
- There are no legal objections to using Zenodo
- There is a limit to the number of (user?) requests for the data on Zenodo. The limit depends on the type of data, but will not pose a problem at this point of the WG. We do not expect hundreds of downloads per minute in the short term.
- Who can delete the data on Zenodo? The author? The curator? There is a DOI, so a link to the dataset exists always. However, the data can be removed. In that case the link will just refer to the metadata.
- On Github we can automize the technical review of data. Each time a data generator provides its scenario, the tool should be able to check automatically for (technical) consistency and compatibility. Additional review may be required.

### Discussion on tasks to work on
- We need to set up a workflow for sharing, harmonizing and combining scenario data. This includes defining:
    - What does the data provider need to do (which format to provide, which metadata to provide)
    - What does the github curator need to do (Which reviews are automized and which are not)
    - Guidelines on how to share scenario data without infringing Ecoinvent rights
    - At what point in the workflow will the data be archived at Zenodo and does this happen automatically or not?

## 09-03-2023

### Discussion on the (larger) Prospective LCA network and communication
- The group has shown interest in joining the Prospective LCA network as a working group.
- This will not change the invested time for the group, but we will use the official channels (website, LinkedIn) for communication and increasing visibility.
- The background working group has two different pillar: software development and more "philosophical" discussions. Github is the best medium for the first pillar, but maybe we need a second medium for the philosophical pillar. We need to think about which medium is good.
- Maybe we need to think about a name when we join the prospective LCA network, there is some confusion about which group is which.

### Brainstorm session about topics that we want to work on
- Distribution and reporting of databases: how to make it easy and transparent. This is work in progress. First steps are unfold and replicate data packages. 
- Making reports of changes that have been done by premise is a next step
- There is also work ongoing to integrate unfold in the Activity Browser
- It could be nice to be able to use the superstructure approach in brightway. However, today this is not straightforward to implement and it requires work from brigthway side. Is not the top priority.
- There is also a need for harmonization of scenario documentation. From premise side, but also in the general scientific literature. Often it is not easy to understand the scenarios that are being descibed. Our working group could develop guidelines on how to do this in a transparent and understandable manner based on our experience with premise.
- Other impact categories could be investigated, because they are not covered by IAMS. Work is ongoing on including scenarios for the Montreal Protocol to better assess ozone depletion. Similar work could be persued for other chemicals (pesticides for example).

### Hosting datbases on Ecoinvent
- This topic will be moved to the next meeting. The general feeling is that it could be possible, but there are some risks to further discuss.

    

