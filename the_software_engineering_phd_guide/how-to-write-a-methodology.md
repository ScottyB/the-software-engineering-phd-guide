# How to write a methodology?

The methodology of a research paper provides the reader with confidence in the findings. A good methodology provides an obvious connection to answering research questions or testing hypotheses. Much has been written about research methodologies and how to present the findings, see [Empirical Standards](https://github.com/acmsigsoft/EmpiricalStandards). In this article I'll focus on how to evaluate your findings. 

The purpose of evaluating your findings is to demonstrate that you have actual findings and that they have not been stumbled upon by accident. Science is designed to move the body of knowledge forward so your findings must be novel, new, and valid, hold for the context you describe. Software engineering is a social-technical design based discipline and for this reason I present knowledge as sitting within a context. Here I show the bias of my research philosophy. In brief, if you have generalisable knowledge that is universally applicable then you are in computer science 

## Provide a justification for your data collection instruments 

Research instrucments refers to the tools and methods you use to collect data. In software engineering, instruments include questionnaires, interview questions, static analysis scripts, and monitoring applications. When writing up your methodology provide evidence or citations that justify the use of these instruments. A common approach in other disciplines is to borrow instruments from papers that have already been published and adapt them to your own research questions. Another approach is to perform an empirical analysis of a dataset and derive quesetions for a survey/interview from the results. When you need to create an instrument from scratch ensure that your methodology provides a thorough evaluation. The purpose of the evaluation is to ensure that the instrument captures the data accurately and robustly i.e. others can collect the same data using your instruments. A growing trend I hope that will continue is the idea of publishing a research study design. Researchers write up their methodology and research questions as a separate report that is peer reviewed. On acceptance, the venue will guarantee to publish the results provided the exact methodology is followed. Publishing research study designs provides 1) feedback on the methodology prior to doing any work, 2) prevents the exclusion of negative results from the literature, and 3) encourages the creation of robust methodologies. I will encourage everyone to publish a study design first. 

## Evaluate the results of your study

Present your findings from following your methodology in a way that directly links to the data. For example, in an interview provide quotes from actual interviewees that support the conclusion you have drawn. Triangulation is important in resarch to provide multiple sources of the same finding. Ensure that your methodology includes an evalution section that answers the question "how do I know these findings are trustworthy?" A standard approach is to use mixed methods see [CITATION]

## Structure the methodology like writing a cooking recipe

When writing up your methodology provide a summary of the key steps especially a) how you created the instruments, b) the number of samples/participants, and 3) how you evaluated the findings. Add a figure at the start of the methodology section showing the core steps. As you write your methodlogy think of a recipe that you would follow to bake a cake. All of the ingredients and the steps required are included in the recipe. Your methodology should enable another researcher to replicate your study and obtain the same findings as you. Identify gaps where subjectivity or randomness is present in your study design and provide a mitigation approach. For example, a study that involves subjectively annotating software defects use multiple annotators and calculate Cohen's Kappa to assess the level of agreement between annotators. Randomness is related to sampling and can be addressed through increasing the sample size or (where applicable) performing a power analysis. No methodology is completely sound, there are always factors that are not considered or are out of scope. Mention these aspects in the threats to validity or future work sections of the paper. 

## Methodology vs Approach

Two confusing terms that appear in research papers are methodology and approach. The methodology is the research framework that describes how the research is conducted it defines **what you will do**. However, the approach describes **how your solution works**. Approach sections are common in tool papers that describe a software artefact, sometimes the approach section is named after the tool being presented. For example, [RAPPT](https://drive.google.com/file/d/1qh5SW3gzMc9-My_DV5Hs8ell1sQu4HC5/view) presents the approach section under the heading `RAPPT`. A tool paper that contains both a methodlogy and an approach section will describe how the research for the tool was conducted in the methodology and the how the tool functions in the approach section.





