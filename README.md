# Writing a System description Paper

In order to be included in our official ranking, you need to write a system description paper. 

Note that you will not have to pay any fees for your paper to get published unless you would like to attend the SemEval workshop, and in this case you will have to check the conference website.


## Should I write a paper even if my system did not perform well?
Yes! 

We would like to hear from all of you even if your results are negative and even if your system does not outperform other systems. 
Please share details about your system and note that in our task description paper, we will have special mentions of systems that are reproducible even if they are not the top performing ones.

Before the system description papers are due, we will share a preprint of our dataset paper that you can use to analyse your results and conduct ablation studies, further discussion, etc.

## Template  

SemEval provides some writing tips [here](https://semeval.github.io/system-paper-template.html). Check also their [FAQs page](https://semeval.github.io/faq.html).


Use the ACL template, see https://acl-org.github.io/ACLPUB/formatting.html. Your paper should include 5 pages in the ACL format System paper submissions for a single task and  up to 8 pages if you are participating in multiple tasks (E.g., SemEval task 11 and SemEval task 1). 
Acknowledgments, references, and appendices do NOT count toward page limits. 

### SemEval Requirements
See [the SemEval requirements](https://semeval.github.io/paper-requirements.html). 

The title should be "Team Name at SemEval-2024 Task N: Descriptive Title".
"at", not "@"  "SemEval" and the year are separated by a hyphen and no spaces, 
E.g., "SemEval-2020"  task number is followed by a colon not a dash colon that has a space after it but not before it.
You can write one paper for multiple tasks:
E.g. 1, ``Team Name at SemEval-YYYY Tasks N1 and N2: Descriptive Title" (2 tasks) 
E.g. 2, ``Team Name at SemEval-YYYY Tasks N1, N2, and N3: Descriptive Title" (3 or more tasks)  
Papers are not anonymous when submitted.

## Structure
You should start with an introduction followed by related work, data, model description, results, analysis, and conclusion. Note that this is an example and you can change this structure depending on what you would like to present. In addition, the length of each section depends on what you would like to focus on.
| **Section** | **Points covered** |
|------- | ------------------------|
|**Abstract** |Summary of your paper. You can highlight the key takes/results.|
|**Introduction**| <p> What is the task about? Why is it relevant/important? <p> What is your approach to solve the problem? <p> * What did you find out or observe while participating in the task? <p> The key results? <p> The struggles? <p> Have you released the code/model? (You are highly encouraged to do so.) <p> Add a URL in this case <p> E.g., see these papers: [1](https://arxiv.org/pdf/2404.01490) [2](https://aclanthology.org/2024.semeval-1.254.pdf) and [3](https://arxiv.org/pdf/2404.02570)|
|------- | ------------------------|

Related Work/ Background
Summarise the most important details about the task.
Summarise work that is related to yours (e.g., approaches that inspired you to go with the presented solution).
Situate your work: 
Explain how it is new/different.
What does it build on?
See some work on our GitHub repository. (Check references.)
E.g., see https://arxiv.org/pdf/2404.02570 
Present key details of publicly available resources used 
System Overview
Key algorithms and modelling decisions/steps in detail.
The resources beyond training data (e.g., lexicons, other data, …).
The maths behind your model and its explanation in plain English
All the variants of your model
E.g., https://aclanthology.org/2024.semeval-1.202.pdf and https://aclanthology.org/2024.semeval-1.254.pdf 
Experimental Setup
Data splits (train/dev/test) and how they are used.
E.g., have you used the dev set to train the final model?
All the details about preprocessing, parameter tuning, … 
You can add more to the appendix
External tools libraries used for pre/post-processing
E.g., https://arxiv.org/pdf/2404.0257, https://aclanthology.org/2024.semeval-1.202.pdf, https://aclanthology.org/2024.semeval-1.254.pdf  
Results
Key findings
How well did your system perform according to the official metrics?
How does it rank in the competition?
Analysis beyond the overall scores
Positive/negative insights.
Quantitative analysis and ablation studies.
Error analysis and negative insights from the results
E.g., Did you notice some patterns in the generated false positives/negatives? 
Investigate further and report your findings!
Observations about the data.
Human evaluation if any
E.g., https://aclanthology.org/2024.semeval-1.202.pdf
Conclusion
Summary of the work and future work
E.g., see all previous papers.
Ethical considerations
Ethical implications of the task/model
Can your model be misused?
Any biases?
Any potential misuses?
See https://aclrollingreview.org/ethicsreviewertutorial as well the ethics shee for emotion analysis https://arxiv.org/pdf/2109.08256 
Acknowledgements and Appendix (Optional)
Acknowledgment
Anyone that you would like to thank? 
Any funding to acknowledge?
Appendix
Any figures/examples/results that are not crucial to the main points in your paper but may help


Paper Examples
Examples of good system description papers that we received for a task that we organised last year:
https://arxiv.org/pdf/2404.01490
https://arxiv.org/pdf/2404.02570
https://aclanthology.org/2024.semeval-1.202.pdf
https://aclanthology.org/2024.semeval-1.254.pdf


Further, you may refer to the papers that received best paper awards at previous SemEval workshops: 
Best papers at SemEval 2024 https://semeval.github.io/SemEval2024/awards

Best papers at SemEval 2023 https://semeval.github.io/SemEval2023/awards
Best papers at SemEval 2022: https://semeval.github.io/SemEval2022/awards

Writing References
https://semeval.github.io/system-paper-template.html
https://writing.wisc.edu/handbook/assignments/writing-an-abstract-for-your-research-paper/
https://web.stanford.edu/class/cs224u/2021/slides/cs224u-2021-presenting-part2-handout.pdf
https://aclrollingreview.org/ethicsreviewertutorial
How to write an okay research paper.
https://medium.com/@vered1986/tips-for-writing-nlp-papers-9c729a2f9e1f

