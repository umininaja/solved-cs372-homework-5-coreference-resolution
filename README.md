Download Link: https://assignmentchef.com/product/solved-cs372-homework-5-coreference-resolution
<br>
In the previous assignment, we addressed the task of extracting relations from the literature in biomedicine and assessed its performance. In this assignment, we will address the problem of coreference resolution, as illustrated in the example text below, where the ambiguous pronoun ‘she’ is noted in bold, and the two potential coreferent names ‘Fujisawa’ and ‘Mari Motohashi’ in italic, with an underline for the correct one:

“In May, <u>Fujisawa</u> joined Mari Motohashi’s rink as the team’s skip, moving back from

Karuizawa to Kitami where <strong>she</strong> had spent her junior days.”

In this example, ‘she’ refers to ’Fujisawa’ but does not refer to ‘Mari Motohashi’. The expected output would be that ‘Fujisawa’ is ‘TRUE’ and ‘Mari Motohashi’ is ‘FALSE’. An ambiguous pronoun may also refer to both of the two coreferent names or none.

For this homework assignment, you are asked to go through the following steps for coreference resolution: (1) Download GAP coreference repository from the link:

<u>https://github.com/google-research-datasets/gap-coreference</u>, (2) develop your program that resolves ambiguous pronouns that refer to names, and (3) assess the performance of your program against 4,000 pairs in gap-test.tsv evaluated by Precision, Recall, F-score, and Bias ratio with two task settings: snippet-context and page-context. Snippet-context indicates that the context (sentences) in the Wikipedia URL cannot be used, and pagecontext indicates that the context can be used. Bias ratio is calculated by taking the ratio of feminine (F) to masculine (M) F1 scores – F/M. Further information about the data can be found from the link above. Note that your program will be evaluated as gap_scorer.py.

As before, you should use techniques that can be implemented in Python and NLTK, scored as a relevance.

<ul>

 <li><u>Write a Python code</u> for coreference resolution based on the repository.</li>

 <li><u>Discuss your results</u>, to explain how you addressed the goal and to suggest how you can improve the quality of the results further. This document must be in English.</li>

</ul>




All the requirements as underlined above must be composed by yourself and without help from anyone else. Any similarity of the results will be flagged for plagiarism and, if found sufficiently similar, penalized, up to, but not limited to, a failure to this homework.