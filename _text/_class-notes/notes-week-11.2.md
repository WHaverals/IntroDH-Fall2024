# Coding in the Humanities

## Why coding?

## What is coding?

- Google Colab:
- Some basic concepts:
  - Variables
  - Data types
  - Functions
  - Loops
  - Conditionals
  - Libraries

- An example
  
## How to learn coding?



## Good Enough Practices

If you have made it this far, we assume you are persuaded that quantitative methods are potentially useful in humanities research. What comes next is up to you. We wrote this book with the hope that it would give students and researchers tools and ideas useful in solving problems and answering questions. We hope that the preceding chapters provided you with some useful resources for your own research.

As you embark on projects which involve data analysis, we invite you to consider the following practices and perspectives. The most important one comes first. It concerns a minimal set of “good enough practices”—a label we borrow from Wilson et al. [2017]—that anyone can and should adopt.

Adopt “Good enough practices in scientific computing”. Wilson et al. [2017] identify a minimal set of practices which “every researcher can adopt, regardless of their current level of computational skill.” They group these practices into six categories (data management, software, collaboration, project organization, tracking changes, and manuscripts). Examples of recommended practices include submission of code and data to a repository (such as arXiv or Zenodo) so others can access and verify results, the use of a version control system (such as git or mercurial) to track all changes over the life of a research project, and the careful preservation of the original (“raw”) data (which should never be edited “in-place”). Adopting these practices does take a modest investment of time and energy. But the benefits are considerable. The practices reduce the incidence of data loss, reduce the time it takes to perform analyses, and facilitate reproduction of results by others.

Start with a problem or a question. If your problem or question is not well-defined, develop or find one which is. Bill James, the fabled baseball statistician, observes that his reputation “is based entirely on finding the right questions to ask”—questions which are currently unanswered but which everyone agrees have answers. James adds that it does not matter if he himself provides the answer to the question, noting, “[if] I don’t get the answer right, somebody else will” [James, 2010]. By focusing on a well-defined question which concerns you or members of some other community, you can make sure your research addresses problems or questions which exist. In doing so, you guard against your work being characterized as a method or dataset in search of a research question. In our experience, such a description often applies to research using new, computationally-intensive methods.

Consider many models. Different narratives are often compatible with the same set of observations. Observed data often renders some narratives more plausible than others. Compare models of past events using held-out validation. Explore how well different models predict (or “retrodict”) observations in a dataset that they have not been shown. (Examples to which the model is not given access are “held-out”.) If you observe a pattern that needs an explanation—e.g., men wearing formal attire in 1900 but not in 2000, women authors writing the majority of novels in 1800 but not 1900 [Lieberson and Lynn, 2003, Tuchman, 1989]—develop a principled model which accounts for what you have observed better than an existing model. In some cases the model will be an implicit naive or “null” model. (In section Nearest neighbors we evaluated the adequacy of a classifier in this way.) Verify that your model is at least as good at predicting observations than the existing model. Share the data and the model with others. They may develop models which are even more credible, in light of the evidence and by the standard of held-out predictive accuracy. And even when they do not, you have done a service by making clear what pattern needs explaining and by enumerating available models. This, in turn, facilitates collaboration by identifying areas of inter-subjective agreement.

Account for variability in human judgments. If your research relies on human labeling or categorization of features of cultural artifacts, verify that different humans agree. Abundant experience teaches us that human judgments vary considerably [Henrich et al., 2010]. Make some effort to indicate that you are aware of this. One minimal strategy for doing this is to have different individuals independently label all or a random subsample of the population of interest. The agreement between these individuals’ labels may then be reported using a measure of “inter-rater reliability”. A simple measure of inter-rater reliability is Cohen’s kappa. More nuanced approaches capable of modeling variability in individuals’ annotation abilities are also available [Passonneau and Carpenter, 2014].

Explore ideas from math and (bayesian) statistics. Good ideas are found everywhere. Academic disciplines and intellectual communities are rarely entirely homogeneous. Do not despair if the presentation of material related to calculus, linear algebra, probability, and statistics fails to resonate with your research interests. We have found that standard textbooks often do not serve students from the humanities and neighboring social sciences particularly well. (Chapters Statistics Essentials: Who Reads Novels? and Introduction to Probability are, in part, attempts at improving this situation.) There are, fortunately, treatments of topics in math and statistics pitched to virtually every audience. Juola and Ramsay [2017] is an example of a math text written for an audience in the humanities. Treatments of probability which we think humanities students and researchers will find appealing include Hacking [2001] and Diaconis and Skyrms [2017].

The practices and perspectives described above have served all of us well in the past. Although induction is often an unreliable guide, we trust that those adopting them will find their efforts rewarded.

