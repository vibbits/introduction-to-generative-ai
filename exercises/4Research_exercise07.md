# Exercise 7:

- Open your browser and surf to https://copilot.microsoft.com

Create feedback based on the MEAL plan.
The MEAL Plan is a structured approach to writing and feedback that stands for:

- Main Idea: The central argument or point of the paragraph.
- Evidence: Supporting details, facts, or data that back up the main idea.
- Analysis: Explanation of how the evidence supports the main idea.
- Link: Connection to the next paragraph or overall thesis.

Use this paper as an example: 
https://www.embopress.org/doi/full/10.1038/s44320-023-00002-9

Prompt:

Create feedback according to this writing exercise following the MEAL Plan feedback scheme. Work stepwise. First create a quick recap of the MEAL Plan feedback scheme. Second, create a summary of the assessment results as detailed in the third step. Third give detailed constructive feedback on the second paragraph of the text fragment below. Use a table with four columns. The first column is the trimmed sentence you identified based on the MEAL plan, second colum is the MEAL plan category, third is a checkbox yes (draft a green mark)/no (draw a red exclamation mark) on the evidence of the MEAL category, fourth column is a brief explanation/suggestion for revision. In the fourth column, comment on the respective intension of the MEAL category and how this is applied. Don't repeat the intension.

Text fragment: 
Gunderson et al, define four types of reproducibility based on the quality of the documentation (Gundersen and Kjensmo, 2018). The lowest degree of reproducibility is “R1 description” that encompasses a textual description of the experiment. “R2 code” contains the code/workflow and its associated metadata but lacks the original data. “R3 data” refers to the available dataset and the associated metadata without the workflow for creating the metadata. “R4 experiments” is the highest degree of reproducibility with dataset, code and associated documentation. 

Addressing reproducibility via documentation inspired multiple initiatives within the field and beyond. These initiatives attempt to standardize the documentation that accompanies the generation of a bioimaging dataset—and by extension other data analysis disciplines. Organizations such as EOSC assert that the quality of data and associated metadata will improve/if it is Findable, Accessible Interoperable, and Reusable (FAIR; Wilkinson et al, 2016), and will enhance the reproducibility of research (https://zenodo.org/records/7515816). The FAIRification of data requires work at many levels from ontology to reproducible analysis pipelines. Recent ontologies such as REMBI (Sarkans et al, 2021), MITI (Schapiro et al, 2022), and EDAM Bioimaging (https://bioportal.bioontology.org/ontologies/EDAM-BIOIMAGING) provide a starting point to report metadata associated with analysis. 

The typical and most common tool for documenting experiments is the electronic labnotebook (Myers et al, 2001), which does not necessarily accommodate the aforementioned standardization of metadata like REMBI, MITI or EDAM. These metadata standards are increasingly incorporated with rich file formats (like OME-TIFF and OME -Zarr) or data tools such as OMERO to find and browse images alongside metadata; https://www.openmicroscopy.org/omero/) and ManGO for associating any file with predetermined metadata on modern data management systems like iRODS (https://irods.org/; https://github.com/kuleuven/mango-metadata-schemas).
