# "Achieving a ML Proof-of-Concept" project : Predicting performances of Youtube videos using their API

This project is done in the context of the "Achieving a ML Proof-of-Concept" course of the Albert School Bachelor cursus.

## Description

We choosed to work with the YouTube API (V3), with the goal of predicting the performances of certain YouTube channels' videos and shorts (so predicting their views, likes, and comments).
The channel we will apply our models to is [Shortcat](https://www.youtube.com/@Shortcat321).

## Environment & Installation

We are working in a .venv (Python 3.11.9).

Use the local package manager [%pip] to install each librairies, while aligning yourself with their versions (in the requirements.txt).

```bash
%pip install pandas
%pip install numpy
%pip install scikit-learn
%pip install xgboost
%pip install lightgbm
%pip install matplotlib
%pip install seaborn
%pip install isodate
%pip install requests
```

## Models

We will use : Random Forest, Ridge, LightGBM, XGBoost.
We will consider every videos before February 2025, as the predictions will be on the long term, seeing how it is not practical to do lauching predictions without historical data.

## Contributing

Pull requests are welcome. No changes to this project are possible by anyone other than this project's members.
But all kind of feedback is welcome!