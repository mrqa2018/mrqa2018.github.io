---
layout: main
title: Home
order: 1
---
**New**: we have released our workshop [program](#program)!


Machine Reading for Question Answering (MRQA) has become an important testbed for 
evaluating how well computer systems understand human language,
as well as a crucial technology for industry applications such as search engines and dialog systems.
The research community has recently created a multitude of large-scale datasets 
over text sources such as 
Wikipedia ([WikiReading](http://www.aclweb.org/anthology/P16-1145), 
[SQuAD](https://aclweb.org/anthology/D16-1264),
[WikiHop](https://arxiv.org/pdf/1710.06481.pdf)), 
news and other articles ([CNN/Daily Mail](https://arxiv.org/pdf/1506.03340.pdf), 
[NewsQA](https://arxiv.org/pdf/1611.09830.pdf),
[RACE](http://aclweb.org/anthology/D17-1082)),
fictional stories ([MCTest](http://aclweb.org/anthology/D/D13/D13-1020.pdf), 
[CBT](https://arxiv.org/pdf/1511.02301.pdf),
[NarrativeQA](https://arxiv.org/pdf/1712.07040.pdf)), 
and general web sources ([MS MARCO](https://arxiv.org/pdf/1611.09268.pdf), 
[TriviaQA](http://www.aclweb.org/anthology/P17-1147), 
[SearchQA](https://arxiv.org/pdf/1704.05179.pdf)).
These new datasets have in turn inspired an even wider array of new question answering systems.

This workshop will gather researchers to address and discuss important research topics
surrounding MRQA, including:
- **Accuracy**: How can we make MRQA systems more accurate?
- **Interpretability**: How can systems provide rationales for their predictions?
- **Speed and Scalability**: How can systems scale to consider larger contexts, from long documents to the whole web?
- **Robustness**: How can systems generalize to other datasets and settings beyond the training distribution?
- **Dataset Creation**: What are effective methods for building new MRQA datasets?
- **Dataset Analysis**: What challenges do current MRQA datasets pose?
- **Error Analysis**: What types of questions or documents are particularly challenging for existing systems?

## Program

8:45--9:00   | Opening remarks
9:00--9:35   | [Phil Blunsom](https://www.cs.ox.ac.uk/people/phil.blunsom/), University of Oxford/Deepmind, Data driven reading comprehension: successes and limitations
9:35--10:10  | [Sebastian Riedel](http://www.riedelcastro.org/), University College London, Reading and Reasoning with Neural Program Interpreters
<button class="btn btn-outline-info" type="button" data-toggle="collapse" data-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
    Abstract
  </button>
<div class="collapse" id="collapseExample">
  <div class="card card-body">
    We are getting better at teaching end-to-end neural models how to answer questions about content in natural language text. However, progress has been mostly restricted to extracting answers that are directly stated in text. In this talk, I will present our work towards teaching machines not only to read, but also to reason with what was read and to do this in a interpretable and controlled fashion. Our main hypothesis is that this can be achieved by a)  the development of neural abstract machines that follow the blueprint of program interpreters for real-world programming languages. We test this idea using two languages: an imperative (Forth) and a declarative (Prolog/Datalog) one. In both cases we implement differentiable interpreters that can be used for learning reasoning patterns. Crucially, because they are based on interpretable host languages, the interpreters also allow users to easily inject prior knowledge and inspect the learnt patterns. We will also present a data generation strategy to produce training sets for tasks that require reading and reasoning, and two datasets we have generated with it: Wikihop and Medhop.
  </div>
</div>
10:10--10:30 | Best paper talk: _A Systematic Classification of Knowledge, Reasoning, and Context within the ARC Dataset_
10:30--11:00 | Morning coffee break
11:00--11:35 | [Richard Socher](https://www.socher.org/), Salesforce Research, The Natural Language Decathlon: Multitask Learning as Question Answering
11:35--12:10 | [Jianfeng Gao](https://www.microsoft.com/en-us/research/people/jfgao/), Microsoft Research, Multi-step reasoning neural networks for question answering
12:10--13:45 | Lunch
13:45--14:20 | [Sameer Singh](http://sameersingh.org/), University of California, Irvine
14:20--15:30 | Poster session (with one-minute spotlight talks)
15:30--16:00 | Afternoon coffee break
16:00--17:00 | Panel discussion


## Important Dates
- ~~Deadline for submission: Monday, April 23, 2018~~  
- ~~Notification of acceptance: Tuesday, May 15, 2018~~  
- ~~Deadline for camera-ready version: Monday, May 28, 2018~~  
- ~~[Early registration deadline](https://acl2018.org/registration): June 4, 2018~~ 
- Workshop Date: Thursday, July 19, 2018

All submission deadlines are 11:59 PM GMT -12 (anywhere in the world). 

## Organization
Steering Committee:
- [Antoine Bordes](https://research.fb.com/people/bordes-antoine/), Facebook AI Research
- [Percy Liang](https://cs.stanford.edu/~pliang/), Stanford University
- [Luke Zettlemoyer](https://www.cs.washington.edu/people/faculty/lsz), University of Washington

Organizing Committee:
- [Eunsol Choi](https://homes.cs.washington.edu/~eunsol/home.html), University of Washington
- [Minjoon Seo](https://seominjoon.github.io/), NAVER & University of Washington
- [Danqi Chen](http://cs.stanford.edu/people/danqi/), Stanford University
- [Robin Jia](http://stanford.edu/~robinjia/), Stanford University 
- [Jonathan Berant](http://www.cs.tau.ac.il/~joberant/), Tel-Aviv University

## Sponsors
![Naver]({{ "/assets/images/naver-logo.png" | absolute_url }})

![Facebook]({{ "/assets/images/facebook-logo.png" | absolute_url }})




