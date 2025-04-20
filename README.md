# stock_predition_model

This README provides instructions for using the pre-trained stock prediction models via the inference.ipynb notebook. Trained Models are available seperately. Just download the weights and load the models.

Model weights should be placed in the same directory as inference.ipynb file

run

pip install -r requirements.txt file

Open the inference.ipynb file.
Load the test data file and the trained model, using joblib.
Preprocess the data exactly the same way as it was done for training.
run the model.predict cell. so it could run the predictions.

Use the output results.

## Note:
- Same training file can be used to train on other data with similar format.
- Model can be safely saved using the same joblib.dump cell.
  
