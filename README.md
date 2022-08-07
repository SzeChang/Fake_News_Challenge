# unReal
## Fake News Classification and Prediction through AI

To run the application, unReal, open the `unReal.ipynb` file and follow the instructions in the Jupyter notebook.

In this implementation, the [BERT base model (uncased)](https://github.com/google-research/bert) was trained and applied for Fake News Stance Detection.

Datasets obtained from [FakeNewsChallenge.org](https://fakenewschallenge.org/).

> IMPORTANT: The model weight used for unReal is too large to be uploaded to GitHub; use the one provided in your copy of the zip file!

---

## GUI Demo Screenshots

This is what you should see if you have followed the steps in `unReal.ipynb` correctly:
![home page](https://github.com/SzeChang/Fake_News_Challenge/blob/1bb7166aca128592d1f29f295dbc9f01dd4ebc4a/GUI%20demo%20pics/home_page.png)

Below is an example of a successful stance detection (expected: `discuss`, output: `discuss`):
![test case good](https://github.com/SzeChang/Fake_News_Challenge/blob/1bb7166aca128592d1f29f295dbc9f01dd4ebc4a/GUI%20demo%20pics/test_case_good.gif)

On the other hand, this is a failed stance detection (expected: `disagree`, output: `agree`):
![test case bad](https://github.com/SzeChang/Fake_News_Challenge/blob/1bb7166aca128592d1f29f295dbc9f01dd4ebc4a/GUI%20demo%20pics/test_case_bad.gif)
