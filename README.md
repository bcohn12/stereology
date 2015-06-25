# stereology
Is stereological sampling effective for non-uniform density distributions?

Effective in what sense, exactly? Stereology is normally used to obtain unbiased estiamtes of cell populations.
However, there are two main (and different) aims in visual ecology: 
(1) topographic distribution of cells
(2) get estimates of total number of cells (photoreceptors, ganglion cells, etc.)



##Research Question

So, maybe we should ask two questions:
(1) How many sampling sites are required to accurately describe the topography of a (sometimes) very complex surface?
(2) Given the non-uniform distribution of cells across the retina, is stereology (optical fractionator) the correct way to estimate the number of cells in the whole retina?


"Is there an optimal number of sampling sites to survey a retinal wholemount, such that it reduces the total number of sites, is still conducive to low-error smoothing, and the result will match an independent sampling on an alternative grid?"

We look to provide reasonable tips for selecting a sample number that guarantees accurate results while minimizing time and effort.

##Methods
Stochastic permutation and consider the robustness of our findings, thereby giving a solid number of sampling sites that would be optimal for the mouse retina.

##Tasks in order:
Secure a retinal sample with high sampling density
Decide on flowchart for entire paper
Decide on what 5 figures to include, and pre-draw PDF versions of them (with hypothesis/fake data) via R.
Write and submit the abstract to Journal via an informal presubmission inquiry.
Introduction, Methods, Results, and Discussion written (with results-based discussion points listed in order)
Code the analysis techniques required to generate the plots.
All figures finalized by 
Manuscript ready for peer review


##What is the problem? 
Cell density mapping of the rear surface of the eye has been a useful and widely used method of visualizing and comparing vision. Used in human-clinical, animal experimental, dissections, and in evolutionary comparisons, retinal mapping has a wide breadth of usage in the scientific community, with X papers with over Y citations in 2014 alone.

##Please summarize the problem domain and statement and the relevance of the problem to the general readership of the journal—in the case of PLOS Computational Biology, the biological research community or a substantial subcommunity. 
What is that subcommunity? How relevant is the problem to them?
##What is the innovation?
We advance the state of the art by identifying two issues in modern cell density mapping:
1. Improper cell density estimation with stereological technique.
2. Improper sample size for cell counts across a retinal wholemount.

We provide a definitive tool for identifying an effective sampling size for a retinal sample, and identified that stereological cell population estimation is unfit for cell density distributions on retinae.

Here it is important that you give enough detail on your contribution to allow the Editorial Board to form an image of the substance and relevance of the advance over the state of the art in the field and over your previous work. If your paper presents material that rests on or is related to your own previous publications, this entails addressing dual publication issues. In order to argue your point, you have to summarize the state of the art on which you base your contribution and give the essential ingredients of your innovation. Depending on the journal, the innovation can take different shapes: a contribution to technology or experimental design, a biological finding, a methodical or theoretical piece of work, etc. For papers in the Methods section of PLOS Computational Biology, the computational method is expected to be at the center of the innovation. This section is not for papers whose methodical core has been published elsewhere and for which you present a—possibly extended or modified—application scenario. Also, studies presenting a comparative assessment of existing methods on an application domain are not within the scope of a Methods paper. We expect a concrete and specific relationship to underlying biological issues. This is why general methods on statistical learning that find their application in biology as well as in other fields of science are typically not considered in scope, unless the paper focuses on sufficiently deep issues of the configuration of the method that are specific to biology. Finally, the method must be the major innovation of the paper. However interesting it may be, a biological finding that has been obtained with methods that are prepublished or only minor modification of prepublished methods is not within the scope of the Methods papers category. (On the other hand, it may be a suitable General research paper for the journal.)
##How is the method validated?
Validation can take manifold forms but is a key element in most scientific papers.
"A validation purely on synthetic data is not sufficient either. Rather, the validation must make a convincing argument for the general applicability of the method in a substantial biological problem domain."


##How is the method being made available?
Our code is available via an Open Source GitHub repository with the MIT license; to maintain code reliability and maintenance, we regenerate all code and figures continuously on Travis-CI and ShareLatex, respectively. To replicate our results, one can clone the repository, follow the usage protocol [Link] and run the code. Our methods are tested in Linux.
