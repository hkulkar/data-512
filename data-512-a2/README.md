# data-512-a1
This directory contains all the code, json, and CSV files required for assignment 1 of DATA 512 Autumn 2020.

The notebook identifies potential sources of bias in the annotated training data of the Perspective API [demo](https://www.perspectiveapi.com/#/home) which is a part of a project called [Conversation AI](https://conversationai.github.io/)

# Findings
The notebook lays out the case that the worker demographics presented may not be represetnative of the general population, and therefore we should be careful when applying the trained model onto other datasets.

For example, the following bar chart shows how the workers were predominantly male:

![Image of gender ratio in worker demographics](Bar chart of gender.png)

## Takeaways & Lessons

<ol>
   <li>Training data can be a source of bias for the model/</li>
   <li>We have to evaluate the details of how a model was trained and its underlying dataset in order to evaluate its fairness and representativeness -- especially if we wish to extend the contexts which it is used in.</li>
</ol>

# To re-run the analysis in jupyter notebook
For easiest setup, download [anaconda](https://www.anaconda.com/), then run

   jupyter notebook

from the directory. Once the notebook is loaded click "run all" cells.

# References
The jupyter notebook leverages two APIs from wikimedia:

# Source of data
You can download the annotated datasets from [here](https://figshare.com/projects/Wikipedia_Talk/16731)
