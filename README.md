# Movie Review Classifier

The purpose of this package is to perform semantic analysis on movie reviews using machine learning. 
It makes use of the [imdb review dataset](http://ai.stanford.edu/~amaas/data/sentiment/) and is based on some excellent
tutorials from Sebastian Raschka in [Python Machine Learning](http://a.co/f2x2HuT).

Note model was originally persisted using scikit-learn version 0.18.1 so if your version is different
you may need to re-persist the model by running
```bash
path/to/python path/to/MovieReviewClassifier/MovieReviewClassifier.py
```

To run this you will need to install python and many scientific packages the easiest
way to get all that is by installing [Anaconda](https://www.continuum.io/downloads)

To run semantic predictions just run 
```bash
path/to/python path/to/MovieReviewClassifier/MovieReviewPredict.py "Movie Review text goes here"
```

Output follows the format Prediction,Probability for example positive,93.5 if the algorithm
is 93.5% sure it is a positive review

With settings as is it is around 90% accurate feel free to further tune it on your own.