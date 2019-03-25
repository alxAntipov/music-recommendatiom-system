>  Music Genre Recommendation system using Convolutional Neural Networks. Implemented in Keras

### Dataset

And how to get the dataset?

1. Download the GTZAN dataset [here](http://opihi.cs.uvic.ca/sound/genres.tar.gz)

Extract the file in the **data** folder of this project. The structure should look like this:

```bash
├── data/
   ├── genres
      ├── blues
      ├── classical
      ├── country
      .
      .
      .
      ├── rock
```

### How to run

To run the training process in the gtzan files:

```bash
$ pip install -r requirements.txt
$ jupyter notebok
```

### File Struct

```bash
train.ipynb - this file contain CNN for train model music classification
predicts.ipynb - this file contain CNN for predict music genres
Reacommendator.ipynb - this file containcluster analsysis
```
