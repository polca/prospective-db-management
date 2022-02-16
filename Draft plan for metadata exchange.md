# Draft plan for metadata exchange

## Brightway Excel LCI format

In general, this needs a more formal specification.

The column labels are fixed by the labels used by Brightway.

### Required attributes for metadata file

* Version
* License
* Author
* Dependencies
* URI

* List of strategies (plus libraries with strategies? Notebooks/python files?)

### Optional attributes for metadata file

* Brightway library versions
* Other optional libraries

### Dependencies & Storage

Brightway can offer storage services for easy download through support from Départ de Sentier, but having something like Zenodo would be preferable.

*Question*: Do we need a "lite" storage to see if data is already present (to avoid unnecessary downloads)?

*Question*: Do we need to invent a unique identifier for LCI databases? Or make up a URI scheme? Is Zenodo download link a good URI?

*Question*: How to handle links to proprietary dependencies?

*Question*: Security of external strategies. Maybe have one "blessed" repo with external strategies?

*Question*: Can we issue DOIs for data? Free versus paid?

*Question*: Do we need "known good result" tests?

### Brightway capabilities needed

Add functionality to import this data, and to download dependent databases

## AB Superstructure scenario format

### Headers

Headers are a mix of fixed values and scenario labels.

**Proposal**: Fix these values and number of columns as currently used.

Scenario labels don't seem to have a naming convention. That's probably fine? But the metadata needs to have more information.

### Required attributes for metadata file

* Version
* License
* Author
* Dependencies
* URI

I don't think we need custom strategies?

### Storage

Same questions apply. In general, these files are larger, but not necessarily large. Chris will clarify if his institution can provide hosting - it would be good to have mirrors at other institutions.