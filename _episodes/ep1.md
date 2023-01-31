---
title: FAIR guiding principles
teaching: 40
exercises: 10
questions:
- What is FAIR? 
- Why is FAIR important?
- Pillars of FAIR
objectives:
- Identify the importance of FAIR principles for the open science
- Explain The difference between FAIR and open data
- Contextualise the main principles of FAIR in the light of the main pillars (Identifiers, access, metadata, and registration)
keypoints:
- FAIR stands for Findable, Accessible, Interoperable and Reusable
- What is meant by FAIRness and FAIRification of data?
- Metadata, identifiers , registration, access are key components in the process of FAIRification
- The FAIR Principles differ from Open data because they permit the owner of the data to control access, although as part of this they are required to define methods and instances where data could be accessed
--- 
##### What is FAIR?
The FAIR Principles were created to help researchers share, reuse, and manage their data. These Principles will be discussed and contextualised later, but for now, you should know that FAIR data can be defined as any dataset that can be discovered and downloaded by others; and interpreted correctly through detailed descriptions of the provision of detailed descriptions about the data.

FAIR is an acronym summarising four principles to help share, reuse, and manage data (Figure 1). FAIR is not limited to the Life Sciences and spans all research disciplines. The FAIR principles are also not limited to data and can be applied to the sharing and reuse of services, software, training and data workflows. 

![Figure 1. Summary of FAIR principles](../fig/fairifying2.png)

Each principle is divided into sub-elements or characteristics.
**Findable**
F1:  (meta)data are assigned a globally unique and persistent identifier
F2: data are described with rich metadata (defined by R1 below)
F3: metadata clearly and explicitly includes the identifier of the data it describes
F4: (meta)data are registered or indexed in a searchable resource
**Accessible**
A1: (meta)data are retrievable by their identifier using a standardised communications protocol
A1.1: the protocol is open, free, and universally implementable
A1.2: the protocol allows for an authentication and authorisation procedure, where necessary
A2: metadata are accessible, even when the data are no longer available
**Interoperable**
I1: (meta)data use a formal, accessible, shared and broadly applicable language for knowledge representation
I2: (meta)data use vocabularies that follow FAIR principles
I3: (meta)data include qualified references to other (meta)data
**Reusable**
R1: meta(data) are richly described with a plurality of accurate and relevant attributes
R1.1: meta(data) are released with a clear and accessible data usage licence
R1.2: meta(data) are associated with detailed provenance
R1.3: meta(data) meet domain-relevant community standards

> ## Important
> In this course, we will contexualize these principle by going through data life cycle which will help you 
> understand **WHY and HOW to FAIR?** rather than going through each principles. However, in our RDMBites, we
> provided quick overview on each of these principles, you can have a look at [FAIR playlist]()
{: .callout}

##### The history of FAIR and its use today
A report from the European Commission Expert Group on FAIR data describes the origins of FAIR and its development in 2014-2015 by a FORCE11 Working Group.  
FAIR is an acronym relating to **any digital object** that is made Findable, Accessible, Interoperable and Reusable. For FAIR data, the “thing” we refer to is the data.  For a script or analysis workflow, the thing would be “software”.
FAIR itself was then formalised and published in 2016 in FAIR Guiding Principles for scientific data management and stewardship.

> ## Exercise
> Read page 11 of [the European Commission report](https://zenodo.org/record/1285272#.Yuk8O_HMIqt), under the 
> heading “Origins and definitions of FAIR”. What benefit did the FORCE11 Working Group see to coining the word FAIR? 
>> ## Solution
>> The report states: “a FORCE11 Working Group coined the FAIR data definition, latching onto an arresting and
>> rhetorically useful acronym. The wordplay with fairness, in the sense of equity and justice, has also been 
>> eloquent in communicating the idea that FAIR data serves the best interests of the research community and 
>> the advancement of science as a public enterprise that benefits society. ”
> {: .solution}
{: .challenge}

> ## Exercise
> FAIR is not limited to data. From [the same report](https://zenodo.org/record/1285272#.Yuk8O_HMIqt), what
> other examples of “objects” can be made FAIR? 
>> ## Solution:
>> On page 15, the report states: “FAIR should be applied broadly to all objects (including metadata,
>> identifiers, software and data management plans (DMPs)) that are essential to the practice of research, and >> should inform metrics relating directly to these objects.” 
>> Also, on page 34 "FAIR data, code, workflows, models, and other digital research objects"”
>> The benefits of FAIR data in research are evidenced in two publications given below as further reading. 
>> Also, you can have a look at our RDMBites on [benefits of FAIR](https://docs.google.com/presentation/d/1xywEzC84RMor46moZVC-H-o3rJqEYYk1/edit#slide=id.p1)
>> {: .solution}
{: .challenge}

**What is meant by FAIRification and FAIRness of data?**
**FAIRification** is the process of making your data FAIR.  In other words, if you add metadata along with your data and share it, you are FAIRifying your data. We will take you through data FAIRification, in detail, later in this course but to put this into context now: by providing metadata along with your data when it is shared, you are FAIRifying your data.
The term **FAIRness** refers to the extent to which your data follows FAIR principles.
A common misconception is to think that for data to be FAIR it needs to be open. FAIR data and oOpen data are different

##### Open science and FAIR

![Figure 2. FAIR data is not open data](../fig/Openfair.PNG)

The Open Data handbook defines Open data as **“data that can be freely used, reused and redistributed by anyone.”**
Hence, “Open data” refers to accessing the data without restriction.  While The term **“open as possible, closed as necessary”** is used commonly when describing FAIR data. However, it is important to note, noting that most FAIR data is open without restriction, though FAIR data doesn’t require to be open and its access can be restricted.but access can be restricted in some cases.  So long as the conditions of access are given, the data remain FAIR even though not open.  The key is in thething is that there should be enough metadata – for a human or computer should be able to find the condition of access expressed in an explicit manner.

> ## Exercise: 
> Why would Open data be sometimes rejected by a clinician?
>> ## Solution:
>> Although not limited to clinicians, researchers reject Open data where they produce and work with sensitive
>> data or data subject to intellectual property.  Protecting sensitive data overrules mandating all research 
>> data should be open access.
>> Note though that in most cases, people following FAIR principles will be looking to share their data 
>> openly. Also, that sensitive data can be released through anonymisation and in many cases, sharing of 
>> sensitive data is subject to controlled access.  
> {: .solution}
{: .challenge}

##### Pillars of FAIR
The FAIR Principles refer to the terms: machine readability, metadata, persistent identifiers, access, and registration. Before we start looking at real data examples that use the FAIR principles, we will start by explaining these first.

**Machine readability**
Machine readability refers to how data can be structured or formatted so that they can be processed or read by a computer.  A spreadsheet is a good example of machine-readable data, where each piece of data (number, word(s)) can be assigned a cell-address in the spreadsheet.  If a programmer knows that all data of a certain type (e.g. patient ID) are in the third column of a datasheet, a script can be written to easily retrieve all patient IDs.  

> ## Exercise
> Based on this definition, does it mean that any digital object is a machine-readable?
>>## Solution:
>> No, for any digital object to be machine readable, two key features should be fulfilled: structure and 
>> format. For instance, if you have a PDF with tabular data, this is not machine readable. Although the 
>> structure is tabular which can be read by computer, the PDF format is not read by machines, it is only 
>> human readable. Examples of machine readable formats are CSV and JSON.
> {: .solution}
{: .challenge}

**Machine readability** is considered one of the main goals of FAIR. Having your data machine readable, will help the reuse of your data and make it findable.

Now, after we discussed machine readability, one of the pillars of FAIR, let's dive in the remainig pillars which will help you understand **WHY AND HOW TO FAIR**

In the next lessons, we will explain to you:
- Metadata
- Persistent identifiers
- Access
- Registration
