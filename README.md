# Predict_Price_from_Text-NLP-Ensemble-Tensorflow-Case_study
Combined / multi input ANN model for NLP

If you’ve got a prediction task where there’s a relatively direct relationship between inputs and outputs, a wide model will probably suffice. Wide models are models with sparse feature vectors, or vectors with mostly zero values. Multi-layer deep networks, on the other hand, have been known to do well on tasks like image or speech recognition, where there may be unexpected relationships between inputs and outputs. If you’ve got a prediction task that could benefit from both of these models (recommendation models or models with text inputs are good examples), wide & deep might be a good fit. In this case, I tried a wide and deep model each separately, then combined them, and found accuracy to be best with wide & deep together.

<img src='image04.png'>

 The wide model is able to memorize interactions with data with a large number of features but not able to generalize these learned interactions on new data. The deep model generalizes well but is unable to learn exceptions within the data. The wide and deep model combines the two models and is able to generalize while learning exceptions.
