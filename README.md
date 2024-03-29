# YouTube Video Classification
Using the Python3 library, scikit learn, we implemented various algorithms tasked with classifying a video into one of ten categories.
The video's title, tags and description are used in the classification.

See report PDF for more information
## How To Use
Clone the repo and then extract **filteredset.7z** from the datasets folder and move it into the same location as *run_tests.py*.

Type python3 run_tests.py to execute.

This will take a long time as it runs seven different algorithms, ten times each, while shuffling the data each time.
## Results
LinearSVC: 85.52%

SVC: 84.20%

Random Forests: 73.00%

Decision Tree: 69.18%

Bernoulli Naive Bayes: 78.26%

Multinomial Naive Bayes: 69.17%

Extra Trees Regressor: 14.96%
