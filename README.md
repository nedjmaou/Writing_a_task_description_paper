# Writing a System description Paper for [SemEval 2025 Task 11](https://github.com/emotion-analysis-project/SemEval2025-Task11)

_The content blogpost is based on content that you will find in the references as well as feedback received when running paper writing tutorials for SemEval2023 Task 12 and SemEval2024 Task 1._

_Some of these points are general so they can be applied to any paper you write._

In order to be included in our official ranking, you need to write a system description paper.  

**Note that you will not have to pay any fees for your paper to get published unless you would like to attend the SemEval workshop. In this case, you will have to check the website of the conference with which SemEval will be co-located.**


## Should I write a paper even if my system did not perform well?
Yes! 

We would like to hear from all of you even if your results are negative or if your system does not outperform other systems. 
Please share details about your model implementation and note that in our task description paper, we will have special mentions of reproducible systems even if they are not the top-performing ones.

Before the system description papers are due, we will share a preprint of our dataset paper. You can use the shared information to analyse your results and conduct ablation studies, further discussion, etc.

## Template  

SemEval provides some writing tips [here](https://semeval.github.io/system-paper-template.html). Check also their [FAQs page](https://semeval.github.io/faq.html).


Use the ACL template, see https://acl-org.github.io/ACLPUB/formatting.html. Your paper should include 5 pages in the ACL format System paper submissions for a single task and up to 8 pages if you are participating in multiple tasks (E.g., SemEval task 11 and SemEval task 1). 
Acknowledgments, references, and appendices do NOT count toward page limits. 


### SemEval Requirements
See [the SemEval requirements](https://semeval.github.io/paper-requirements.html). 

- The title should be **"Team Name at SemEval-2024 Task N: Descriptive Title"**.
  - "at", not "@"  "SemEval" and the year are separated by a hyphen and no spaces, 
  - **E.g.,** "SemEval-2020"  task number is followed by a colon not a dash colon that has a space after it but not before it.
- You can write one paper for multiple tasks:
  - **E.g. 1,** _``Team Name at SemEval-YYYY Tasks N1 and N2: Descriptive Title"_ (2 tasks).
  - **E.g. 2,** _``Team Name at SemEval-YYYY Tasks N1, N2, and N3: Descriptive Title"_ (3 or more tasks)  .
- Papers are not anonymous when submitted.

## Structure
You should start with an introduction followed by related work, data, model description, results, analysis, and conclusion. 
Note that this is an example and you can change this structure depending on what you would like to present. In addition, the length of each section depends on what you would like to highlight.
| **Section** | **Points covered** |
|------- | ------------------------|
|**Abstract** |Summary of your paper. You can highlight the key takes/results.|
|**Introduction**| <p> - What is the task about? Why is it relevant/important? <p> - What is your approach to solving the problem? <p>  - What did you find out or observe while participating in the task? <p>	  &nbsp;&nbsp;&nbsp;&nbsp;- What are the key results? <p> 	 &nbsp;&nbsp;&nbsp;&nbsp;- What are the struggles? <p> - Have you released the code/model? (You are highly encouraged to do so.) <p> 		 &nbsp;&nbsp;&nbsp;&nbsp;- Add a URL in this case. <p> - **E.g.,** see these papers: [1](https://arxiv.org/pdf/2404.01490) [2](https://aclanthology.org/2024.semeval-1.254.pdf), and [3](https://arxiv.org/pdf/2404.02570).|
|**Related Work/Background**| <p> - Summarise the most important details about the task. <p> - Summarise work related to yours (e.g., approaches that inspired you to go with the presented solution). <p> - Situate your work: <p>   &nbsp;&nbsp;&nbsp;&nbsp;- Explain how it is new/different.<p>   &nbsp;&nbsp;&nbsp;&nbsp;- What does it build on?<p>   &nbsp;&nbsp;&nbsp;&nbsp;- See some work on our GitHub repository. (Check references.)<p>**E.g.,** see [this paper](https://arxiv.org/pdf/2404.02570). <p> - Present key details of publicly available resources used.|
|**System Overview**|<p>- Key algorithms and modeling decisions/steps in detail.<p> - The resources beyond training data (e.g., lexicons, other data,...). <p>- The maths behind your model and its explanation in plain English. <p> - All the variants of your model <p>- **E.g.,** [1](https://aclanthology.org/2024.semeval-1.202.pdf) and [2](https://aclanthology.org/2024.semeval-1.254.pdf).|
|**Experimental Setup** |<p>- Data splits (train/dev/test) and how they are used. <p> &nbsp;&nbsp;&nbsp;&nbsp;- **E.g.,** have you used the dev set to train the final model? <p>- All the details about preprocessing, parameter tuning, ... <p>- You can add more to the appendix. <p> - External tools libraries used for pre/post-processing. <p>- **E.g.,** See [1](https://arxiv.org/pdf/2404.0257), [2](https://aclanthology.org/2024.semeval-1.202.pdf), and [3](https://aclanthology.org/2024.semeval-1.254.pdf). 
|**Results**|<p>Key findings <p> - How well did your system perform according to the official metrics?<p> - How does it rank in the competition?<p> - Any analysis beyond the overall scores?<p>  &nbsp;&nbsp;&nbsp;&nbsp;- Positive/negative insight?<p> - Any quantitative analysis and ablation studies.<p> - Any error analysis and negative insights from the results<p>  &nbsp;&nbsp;&nbsp;&nbsp;- **E.g.,** Did you notice some patterns in the generated false positives/negatives? <p>  &nbsp;&nbsp;&nbsp;&nbsp;- Investigate further and report your findings!<p> - Observations about the data.<p> - Human evaluation if any.<p> - **E.g.,** See [this paper(https://aclanthology.org/2024.semeval-1.202.pdf).|
|**Conclusion**| - Summary of the work and future work. <p> - **E.g.,** see all previous papers.|
|**Ethical considerations (Encouraged)**|<p>- Ethical implications of the task/model.<p> - Can your model be misused? If so, how? (Potential misuses?) <p> - Any potential biases? <p> - See https://aclrollingreview.org/ethicsreviewertutorial as well [the ethics sheet for emotion analysis](https://arxiv.org/pdf/2109.08256).| 
|**Acknowledgment (Optional)**|- Anyone you would like to thank? <p> - Any funding to acknowledge?|
|**Appendix (Optional)**|- Any figures/examples/results that are not crucial to the main points in your paper but may help.|


## Examples
- Examples of good system description papers that we received for [SemEval2024 Task 1](https://semantic-textual-relatedness.github.io) organised last year: [1](https://arxiv.org/pdf/2404.01490), [2](https://arxiv.org/pdf/2404.02570), [3](https://aclanthology.org/2024.semeval-1.202.pdf), [4](https://aclanthology.org/2024.semeval-1.254.pdf), [5](https://dial.uclouvain.be/pr/boreal/object/boreal%3A288252/datastream/PDF_01/view), [6](https://arxiv.org/pdf/2410.10585), and others.

- Further, you may refer to the papers that received best paper awards at previous SemEval workshops: 
  - Best papers at SemEval 2024: https://semeval.github.io/SemEval2024/awards</li>
  - Best papers at SemEval 2023: https://semeval.github.io/SemEval2023/awards</li>
  - Best papers at SemEval 2022: https://semeval.github.io/SemEval2022/awards</li>

## References
- **SemEval Guidelines**: https://semeval.github.io/system-paper-template.html

- **Writing an abstract for your research paper**: https://writing.wisc.edu/handbook/assignments/writing-an-abstract-for-your-research-paper/

- **Presenting your research: Writing NLP papers** by Christopher Potts: https://web.stanford.edu/class/cs224u/2021/slides/cs224u-2021-presenting-part2-handout.pdf

- **Ethics Reviewer Tutorial** by ARR: https://aclrollingreview.org/ethicsreviewertutorial

- **How to write an okay research paper** by Sasha Rush: https://www.youtube.com/watch?v=qNlwVGxkG7Q

- **Tips for Writing NLP Papers** by Vered Schwartz: https://medium.com/@vered1986/tips-for-writing-nlp-papers-9c729a2f9e1f

