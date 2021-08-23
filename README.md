# Cat-vs-Dog-Binary-Classification

This is a Cat vs Dog classification model trained via Transfer Learning from MobileNetV2 model.

To pull and use this project:

1) Clone this repo or download it as zip file
2) Extract the contents and install the requirements from the requirements.txt file using
```
pip install -r requirements.txt
```
3) Run the ```cat-and-dog-classification-train.ipynb``` file to train from the training dataset and save the model to a file ```model.h5```
4) Then with the saved ```model.h5``` you can run the ```cat-and-dog-classification-predict.ipynb``` which will predict the given images and store the predictions in ```predictions.csv``` file
