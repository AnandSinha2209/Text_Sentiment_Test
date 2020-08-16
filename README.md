# Text_Sentiment_Test

### Version 1

1) This a test for the machine learning Text Sentiment Detection.
2) This is not the final result and only the  ***first iteration***.
3) This Design has a supervised learning algorithm for classification using one of these TextClassification datasets.
4) The Dataset is taken from the Pytorch repos.
5) This uses the **ngram** approach for the classification and could be made using bi-gram and tri-gram approaches also.
6) Testing using the aforementioned resources theoretically will give a better training split.
7) But Since the Loss Function of this was already low I have not Uploaded it yet.
8) The  results for the run was 
    - **Loss: 0.0237(test)      |       Acc: 90.5%(test)**
9) In the Future we will impliment this and try it again.


### Version 2

Total Code Change along with a few more details and Calulations.

Used Binary Cross Entrol and Sigmoid Functions.

**Loss Function: 0.000**


The Dataabase can be used using the following command :

```sh
DATA_PATH = 'data/imdb_reviews.csv'
if not Path(DATA_PATH).is_file():
    gdd.download_file_from_google_drive(
        file_id='1zfM5E6HvKIe7f3rEt1V2gBpw5QOSSKQz',
        dest_path=DATA_PATH,
    )
```

Dependencies for running the above code snippet is [Google_Drive_Downloader](https://pypi.org/project/googledrivedownloader/) .

```sh
$ pip install googledrivedownloader
```

Permissions for use ->

> This repo can be forked after a mail to me and you are free to contribute to it.
