# concordance
Term concordances for each course in the SANS DFIR curriculum.  Used for automated index generation.

## Background
To allow index generation, a list of words (called a concordance) is needed.  Each word in this list is located in the source material, then the location of each instance noted in the resulting index.

In this case, the files in this repository will be used to feed @joswr1ght's most awesome Python script, which searches PPTX files as source material and generates a DOCX file containing the index.  SANS students will receive this index as a guide to the material and a starting point for their own indexes to use in GIAC testing, if desired.

## Contributing
Josh's script uses a flexible syntax for the word list.  You can simply specify one word per line in the concordance, or use a very robust and powerful syntax to "fine-tune" the index content. To learn more about the syntax itself, see the "[Building a Concordance](https://github.com/joswr1ght/pptxindex#building-a-concordance)" section of his repository.

Anyone wishing to contribute new terms, refine existing search terms, etc should submit a pull request to this repository.  Each respective course author will review PRs and test against new versions of their material.  Helpful terms will be merged and contributors will receive all appropriate SANS and GitHub karma for their submissions.
