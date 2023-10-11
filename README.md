# Python Text Mining

[Text mining](https://en.wikipedia.org/wiki/Text_mining) implementation in Python using nltk toolkit.

### Running the notebook

The code was written in Python across Jupyter notebooks. It was developed in Google Colab which is a free Jupyter notebook environment that allows you to run code through a browser.

Follow [this link](https://drive.google.com/file/d/1FdYbDWPQcph9kOHIIkD4RCAtXY7ugCid/view?usp=sharing) to open the notepad with this code and click on Google Colaboratory.

# Samples

### Datasets

Three different texts were taken from Ray Bradbury's book, novel Fahrenheit 451.

### Analysis

Let's estimate the total number of words and the number of unique words after each processing stage.

**Text 1**
| Stage | Total | Unique |
|---|---|---|
|Tokenization|	419 |	224 |
|Filtering | 224 |	186 |
|Stemming |	224 |	184 |

**Text 2**
| Stage | Total | Unique |
|---|---|---|
|Tokenization|	367 |	199 |
|Filtering |	190 |	142 |
|Stemming |	190 |	133 |

**Text 3**
| Stage | Total | Unique |
|---|---|---|
|Tokenization|	401 |	188 |
|Filtering |	181 |	131 |
|Stemming |	181 |	121 |

Let's plot a graph of word frequency and Zipf's graph.

<img src="https://github.com/Nekhocheninov/TextMining/blob/main/img/img_1.PNG" width="800">

<img src="https://github.com/Nekhocheninov/TextMining/blob/main/img/img_2.PNG" width="800">

Let's evaluate the similarity of the graphs, for this we will use the standard deviation.

| № | Value |
|---|---|
|Text 1|	0.08716 |
|Text 2 |	0.08444 |
|Text 3 |	0.07902 |

The obtained values ​​indicate that the frequency corresponds to Zipf's law.

Set the range of significant words and determine the values ​​of the given range.

<img src="https://github.com/Nekhocheninov/TextMining/blob/main/img/img_3.PNG" width="800">

The indicated ranges describe the content of the texts and contain the following words:

**Text 1:**
*['pleasur', 'see', 'thing', 'eaten', 'see', 'thing', 'blacken', 'chang', 'brass', 'nozzl', 'fist', 'great', 'python', 'spit', 'venom', 'kerosen', 'upon', 'world', 'blood', 'pound', 'head', 'hand', 'hand', 'amaz', 'conductor', 'play', 'symphoni', 'blaze', 'burn', 'bring', 'tatter']*

**Text 2:**
*['went', 'open', 'door', 'montag', 'watch', 'window', 'beatti', 'drove', 'away', 'gleam', 'yellow', 'flame', 'colour', 'beetl', 'black', 'char', 'colour', 'tyre', 'across', 'street', 'way', 'hous']*

**Text 3:**
*['mani', 'hand', 'held', 'warmth', 'hand', 'without', 'arm', 'hidden', 'dark', 'hand', 'motionless', 'face', 'move', 'toss', 'flicker', 'firelight', 'known', 'fire', 'could', 'look', 'way', 'never', 'thought', 'life', 'could', 'give', 'well', 'take', 'even', 'smell', 'differ', 'long', 'stood']*
