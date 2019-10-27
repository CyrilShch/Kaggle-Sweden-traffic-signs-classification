# Kaggle-Sweden-traffic-signs-classification

Categorize the signs of Sweden!

This dataset is really small! I had to use transfer learning and another datasets (with traffic-signs) to improve your score.

**Metric** 

The metric in this competition is Mean F1-Score. F1-the measure is calculated based on the accuracy p and completeness r. Accuracy is the ratio of true positives (tp) to all predicted positives (tp + fp). Completeness is the ratio of true positives to all actual positives (tp + fn). 

**Important**: The final score is F1 averaged across all classes.

**Results**

I have used all following tools:

transfer learning(fine tuning)
data processing
evaluation of the model.

I decided to train model on extra dataset (GTSRB - German Traffic Sign Recognition Benchmark): https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign/

And it was right decision because of small provided dataset.

I was actively using the GPU on Google Colab, because convolutional neural networks learns many times faster.

Finally, I managed to take 3rd place out of 128 place (Top 3%). That's my best performance on Kaggle competitions.

The results are presented in the notebook.
