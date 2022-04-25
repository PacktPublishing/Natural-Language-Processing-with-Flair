# Natural Language Processing with Flair

<a href="https://www.packtpub.com/product/natural-language-processing-with-flair/9781801072311?utm_source=github&utm_medium=repository&utm_campaign=9781801072311"><img src="https://static.packt-cdn.com/products/9781801072311/cover/smaller" alt="Natural Language Processing with Flair" height="256px" align="right"></a>

This is the code repository for [Natural Language Processing with Flair](https://www.packtpub.com/product/natural-language-processing-with-flair/9781801072311?utm_source=github&utm_medium=repository&utm_campaign=9781801072311), published by Packt.

**A practical guide to understanding and solving NLP problems with Flair**

## What is this book about?
Flair is an easy-to-understand natural language processing (NLP) framework designed to facilitate training and distribution of state-of-the-art NLP models for named entity recognition, part-of-speech tagging, and text classification. 
Flair is also a text embedding library for combining different types of embeddings, such as document embeddings, Transformer embeddings, and the proposed Flair embeddings.

This book covers the following exciting features: 
* Gain an understanding of core NLP terminology and concepts
* Get to grips with the capabilities of the Flair NLP framework
* Find out how to use Flair's state-of-the-art pre-built models
* Build custom sequence labeling models, embeddings, and classifiers
* Learn about a novel text classification technique called TARS
* Discover how to build applications with Flair and how to deploy them to production

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/B09NC5XJ6D) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>


## Instructions and Navigations
All of the code is organized into folders.

The code will look like the following:
```
from flair.data import Sentence
from flair.tokenization import SpaceTokenizer

tokenizer = SpaceTokenizer()
s = Sentence('Some nice text.', use_tokenizer=tokenizer)

print(s)
```

This repository contains Jupyter notebooks containing code snippets from the book _Natural Language Processing with Flair_ published ba Packt Publishing. Each notebook belongs to one chapter in the book.

Before running the notebooks make sure to install Flair version 0.11 by running:
```
pip install flair==0.11
```

### Contributing

Feel free to suggest code changes to the book as part of opening an issue or a pull request.

**Following is what you need for this book:**
This book is for data scientists, machine learning engineers, and ML practitioners in both academia and industry. A fundamental understanding of machine learning concepts and working knowledge of Python programming is assumed. Prior experience implementing ML/DL models with TensorFlow or PyTorch will be beneficial. 
You'll find this book useful if you are interested in using distributed systems to boost machine learning model training and serving speed.

### Software and Hardware List


| Chapter  | Software required                    | OS required                        |
| -------- | ------------------------------------ | -----------------------------------|
| 1-12	   | Flair 0.11                           | Windows, Mac OS X, and Linux (Any) |
| 1-12	   | Flask 2.0.3                          | Windows, Mac OS X, and Linux (Any) |

Detailed instructions about how to set up your local environment and install the Python
packages can be found in Chapter 1, Introduction to Flair

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://static.packt-cdn.com/downloads/9781801072311_ColorImages.pdf).


### Related products <Other books you may enjoy>
* Mastering spaCy [[Packt]](https://www.packtpub.com/product/mastering-spacy/9781800563353?utm_source=github&utm_medium=repository&utm_campaign=9781800563353) [[Amazon]](https://www.amazon.com/dp/B093Q3XMF9)

* Distributed Machine Learning with Python [[Packt]](https://www.packtpub.com/product/distributed-machine-learning-with-python/9781801815697?utm_source=github&utm_medium=repository&utm_campaign=9781801815697) [[Amazon]](https://www.amazon.com/dp/1801070032)

## Get to Know the Author
**Tadej Magajna**
is a former lead machine learning engineer, former data scientist, and now
a software engineer at Microsoft. He currently works in a team responsible for language
model training and building language packs for keyboards such as Microsoft SwiftKey. He
has a master's degree in computer science. He started his career as a 15-year-old at a local
media company as a web developer and progressed toward more complex problems. He
has tackled problems such as NLP market research, public transport bus and train capacity
forecasting, and finally, language model training in his current role. Currently, he is based
in his hometown of Ljubljana, Slovenia


