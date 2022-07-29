---
title: FAIRification of data
teaching: 40
exercises: 10
questions:
- How to make data FAIR?
- Checklists and tools for making FAIR
- FAIR micropublication

objectives:
- To learn guiding principles of FAIR
- To understand how to apply FAIR to your data
- To understand the principles of micropublications
- To learn the benefits and challenges of FAIRification of micropublication platform 
keypoints:
- Biosciences are useful software tools suitable for tractability of biomedical research.
- Micropublication platforms can provide findings directly in line with the FAIR principles
---

## How to make data FAIR

FAIR defines a set of principles enabling FAIRification of data, but does not prescribe an absolute standard.  There are examples of different communities in the Life Sciences interpreting and adding context to FAIR through providing checklists, suggestions and frameworks describing the FAIRification of specific data types and files.  We show examples of these later in this course and reference GOFAIR (https://www.go-fair.org/fair-principles/fairification-process/) which covers a broad community of Life Science data, and FAIR in training materials (https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007854).

> ## Further reading
> Wilkinson, M.D. et al. 2016. The FAIR Guiding Principles for scientific data management and stewardship. Scientific Data 3: 160018.
> Cooper, H. 2018. What is this about Research Data? [https://www.howtofair.dk/how-to-fair/documentation/]
> 
{: .callout} 
___

## Checklist for making FAIR

Using a checklist to FAIRify your data is probably the best place to start.  Here you look to score your dataset by creating a tally of principles that your data satisfies.  

Before you start using checklists, it is worth familiarising yourself with a number of terms used commonly in FAIR.  In a minute we will show you 3 checklists that make reference to the following terms:

**persistent identifier**: a unique ID you assign to you data which never changes and is never retired.  This ID helps you reference, locate (and download) your data.  Examples of persisten identifiers include: **E-MTAB-8316** (https://www.ebi.ac.uk/biostudies/ArrayExpress/studies/E-MTAB-8316) and **GIVE THE ZENODO EXAMPLE!!**  (https://en.wikipedia.org/wiki/Persistent_identifier)

**metadata**: is a description your data.  In an Excel sheet, for example, column heading are metadata (decriptions) about the data in the column they describe.  Metadata can also work at a high level where data are affiliated to creators, contact details and provenance (https://en.wikipedia.org/wiki/Metadata)

**controlled vocabularies**: a dictionary of terms you use to write your metadata and data.  For example, when working with clinical data and defining "sex at birth" as a variable, you would used a controlled vocabulary of ["male", "female", "unknown"] to control data entry.  The use of controlled vocabularies prevents confusion and duplication caused by using free text, for example ["male", "Male", "man", "m", "female", "FEMALE", "woman", "unknown", "blank", "n/a"], noting that free-text requires curation (correction) before analysis can occur.

### Examples

The checklist examples we have chosen to showcase include the published FAIR Guiding principles, as well as examples where these have been positioned for different data communities.

First, we have the FAIR principles published in 2016 (https://www.nature.com/articles/sdata201618), where each bullet can be "asked" of the data:

![FAIRchecklist01](../fig/FAIRchecklist01.png)

Secondly, we have a checklist published by Sarah Jones & Marjan Grootveld EUDAT, CC-BY-SA ((https://zenodo.org/record/1065991/files/How-FAIR-are-your-data.pdf?download=1) based on the published principles:

![FAIRchecklist02](../fig/FAIRchecklist02.png)

Thirdly, we have an example where the FAIR principles are applied to define a checklist of 10 princples for the prepariton of FAIR training materials (https://doi.org/10.1371/journal.pcbi.1007854).

![FAIRchecklist03](../fig/FAIRchecklist03.png)

{: .callout}

> ## Test your knowledge
> Describe data FAIRification in your own words
> Which FAIR checklist would you use and why?
> Google to see if their are FAIR checklist for your own community and data
{: .challenge}
___


