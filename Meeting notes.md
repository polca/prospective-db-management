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

