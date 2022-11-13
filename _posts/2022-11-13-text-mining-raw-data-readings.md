---
layout: post
published: true
category: commentary
title: Text Mining & Raw Data Readings
author: Daniel Kessler
tags:
  - Digital_Humanities
---
**Notes on Text Mining Readings:**

**How these techniques have become standard:**
- As defined by Marti Hearst (“the discovery by computer of new, previously unknown information, by automatically extracting information from different written resources”), text mining has certainly become a standard method of data extraction. His “linking together of extracted information” is reflected in the natural structural format of the extractions (e.g., JSON, CSV), which acts as a sort of dictionary to provide multiple levels of metadata. 
- Hearst imagines text mining as primarily useful when we don’t know much about the information we’re planning to extract: but this is not always the case. Today, we often mine text about which we know very much, but whose specific details we don’t have in a manner conducive to our research. For example: one can go to a website and, depending on the situation, see the pertinent textual data there – but using the browser interface alone, and without text mining, this data can’t always be formatted in ways that allow for the desired analyses. Then again, Hearst wouldn’t purely call this “‘real’ text mining… that discovers new pieces of knowledge.”
- What Hearst earlier called text mining has now become an essential element of textual analysis within natural language processing. Today, “extraction” and “analysis” are sometimes combined within a single function, which leads to a blurring of the lines between these disparate tasks. In the example of topic modeling, for example, this process has been merged. Visualizations, and references to external libraries that allow any number of advanced functionalities, have also been incorporated within individual Python files. Topic modeling and other NLP methods also introduce far more advanced methods of organizing information into n-dimensional matrices that were not envisioned as components of text mining. Part of the job of text mining, after all, is to organize the text into discrete units that can be called upon when needed.


**Potentials or shortcomings that were envisioned, but wasn’t realized, or were superseded:**
- Text mining was envisioned as entirely separate from search tools. But it can still be used to conduct advanced searches of websites and web-based databases.
- Text mining was also envisioned as separate from (non-textual) data mining, but today, the same processes may be used for both, depending on the tool or combination of tools (e.g., API, Python, etc.). 
- Some of what Hearst defines as text mining now falls under the umbrella of psycholinguistics (e.g., LIWC), although it performs similar functionality.


**Notes on Raw Data Reading:**
- As suggested in earlier readings – through which we learned that no data is “given” – here, we observe that no data is truly raw. All data is constructed and selected. All data is “cooked” to one degree or another.
- Here, we can see that depending on the discipline, data is cooked differently; it is extracted, shaped, and interpreted differently. Even data within fields can be cooked differently (as illustrated by the author’s example of varying versions of Milton poems). 
- As the author notes, “data need us.” Data does not exist without human extraction, observation, analysis, composition. The fact that data, the plural of datum, is used more commonly also illustrates the widespread need for multiples in our data: not only does data need us, but we need data, and to accomplish all manner of tasks, we need as much data as we can get. That said, a unique distinction of Gitelman and Jackson’s is interesting to consider: “The singular datum is not the particular in relation to any universal (the elected individual in representative democracy, for example) and the plural data is not universal, not generalizable from the singular; it is an aggregation. The power within aggregation is relational, based on potential connections: network, not hierarchy.”
- Usability is also addressed in this chapter. Notably, data must be usable for the duration of a study, and for future researchers. This means that data must be “as raw as possible,” in a sense. Otherwise, it may be ideal for it to be annotated in such a way that its “original” can be extracted and used in a new context.
