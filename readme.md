# Sentiment Analysis (Python3)

### Table of Contents

- [Project Description](#description)
- [Dataset](#design-constraints)
- [Technologies](#technologies)
- [Repository Contents](#repository-contents)
- [How To Use](#how-to-use)
- [License](#license)


---

## Project Description

The challenge involves classifying product reviews from Yelp, IMDB and Amazon as either positive or negative; given
the text of a review comment as input. The focus of this exercise is on a field within machine learning called Natural Language Processing.

The goal is to predict sentiment -- the emotional intent behind a statement -- from text. For example, the sentence: "This movie was terrible!" has a negative sentiment, whereas "loved this cinematic masterpiece" has a positive sentiment.

To simplify the task, we consider sentiment binary: labels of 1 indicate a sentence has a positive sentiment, and labels of 0 indicate that the sentence has a negative sentiment.

#### Dataset
The dataset is split across three files, representing three different sources -- Amazon, Yelp and IMDB. 
The task is to build a sentiment analysis model using both the Yelp and IMDB data as your training-set, 
and test the performance of your model on the Amazon data.

Each file can be found in the input directory, and contains 1000 rows of data. Each row contains a sentence, a tab character and then a label -- 0 or 1.

#### Technologies

Please refer to the **requirements.txt** file for complete Python (Conda) environment specifications

#### Repository Contents

-- **sentiment_notebook.ipynb** iPython (Jupyter) Notebook containing code and relevant markdown text

-- **requirements.txt** contains a list of the installed python packages. Users can then install all the necessary packages
```
conda install --file requirements.txt
```
-- **input** directory contains three text-based files (datasets) required for this project

-- **.gitignore** file contains a list of superfluous files and can be ignore


[Back To The Top](#read-me-template)

---


## License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[Back To The Top](#read-me-template)