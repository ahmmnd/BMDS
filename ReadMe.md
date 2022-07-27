# The Birth of the Modern Detective Story (BMDS) Dataset


## Data and Annotation
The BMDS Dataset contains texts, annotations, and metadeta for detective stories published between 1890–1920. 
* The stories are provided in plain text and with Dublin core metadata for stories and authors. 
* Each story is annotated for 61 categories related ot types of crimes, clues, and evidence represented

Story-level annotations and metadata can be found in the `BMDS_story_annotations.csv` file. This file includes a unique `Story Code` for each story, which corresponds to the name of the plain text version of the story, which can be found in the `texts/` folder. It also includes an `Author Code` for each story (two in the case of co-authored stories), which correspond to the author-level metadata in the `BMDS_author_metadata.csv` file.


### Annotation Guidelines

The full text of the annotation guidelines that were used to prepare this dataset can be found at [this link](https://docs.google.com/document/d/1G62El8Tj5SWBQ5QYFDElJGFtihjIoi2NkkwdaAzhQvI/edit#heading=h.zezkqyi0lm8z). These guidelines present detailed descriptions of all terms and categories used in the dataset.

### Data Description

The `BMDS_story_annotations.csv` contains the following columns, all of which are defined the Annotation Guidelines linked above.
* `Story Code`

#### Annotations
* `Annotator #1 Code`: unique code of first BMDS annotator who produced the annotations
* `Annotator #2 Code`: unique code of second BMDS annotator who produced the annotations
* `Story Title`
* `Plot Summary`
* `Content warnings`
* `Author Code`
* `Second author code (if applicable)`
* `Investigation-reveal order`
* `Reveal border sentence`
* `Name of Detective #1`
* `Detective #1 Gender`
* `Detective #1 Role`
* `Name of Detective #2`
* `Detective #2 Gender`
* `Detective #2 Role`
* `Number of detectives if more than 2`
* `Name of Assistant #1`
* `Assistant #1 Gender`
* `Assistant #1 Role`
* `Name of Assistant #2`
* `Assistant #2 Gender`
* `Assistant #2 Role`
* `Number of assistants if more than 2`
* `Number of victims of gender Male`
* `Number of victims of gender Female`
* `Number of victims of gender Non-binary`
* `Number of victims of gender Unknown`
* `Number of victims who are corporate entities`
* `Number of culprits of gender Male`
* `Number of culprits of gender Female`
* `Number of culprits of gender Non-binary`
* `Number of culprits of gender Unknown`
* `Culprits introduced during reveal?`
* `Main culprit independence`
* `Initiator of investigation`
* `Role of police`
* `Focus on crime or quasi-crime`
* `Crime trajectory`
* `Occurrence of crime or mystery`
* `Types of qrimes`
* `Motives`
* `Means (murder only)`
* `Sufficient clues to guess?`
* `Sufficient clues to solve?`
* `Correct annotator guess?`
* `Types of clues`
* `Essential clue`
* `Type of essential clue`
* `Most salient clue`
* `Type of most salient clue`
* `Red herring description`
* `Type of red herring`
* `Presence of planted or fabricated evidence`
* `Types of evidence made available`
* `Is the crime solved?`
* `Decision NOT to alert authorities?`
* `Satisfying narrative account?`
* `How satisfying as detective fiction?`
* `Recommend to friend?`

#### Metadata
* `Date of First Publication (YYYY-MM-DD)`
* `Format of First Publication (Journal or Book)`
* `Name of Journal or Title of Book`


The `BMDS_author_metadata.csv` file contains the following columns:
* `Author Code`: Corresponds to `Author Code` field in `BMDS_story_annotations.csv`
* `Surname(s)`
* `Given Name(s)`
* `Sex`
* `Date of Birth (YYYY-MM-DD)`
* `Country of Birth`
* `City/Town of Birth`
* `Date of Death (YYYY-MM-DD)`
* `Country of Death`
* `City/Town of Death`
* `Nationality/ies`
* `VIAF`: link to VIAF for author


## Contact
- [Adam Hammond](https://www.adamhammond.com/) (Department of English, University of Toronto)
- [Simon Stern](https://www.law.utoronto.ca/faculty-staff/full-time-faculty/simon-stern) (Faculty of Law & Department of English, University of Toronto)

Email: adam.hammond@utoronto.ca, simon.stern@utoronto.ca