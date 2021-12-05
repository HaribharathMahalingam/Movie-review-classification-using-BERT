# Movie-review-classification-using-BERT
Classifying movie reviews as Positive or Negative using DistilBert and Tensorflow

Step1: install random, numpy, tensorflow, keras, transformers. 

Step2: import AutoTokenizer, TFAutoModel from transformers. 

Step3: Read maximum n text files from folder and returns them as a list of list of text and its class label cl. 

Step4: Read maximum n positive and maximum n negative text example from the respective folders. Randomizes them. Return the list of text and an np.array of corresponding one-hot class labels [1,0] for pos and [0,1] for neg. 

Step5: Read the data for training and testing purpose.

Step6: tokenize the training and test set. 

Step7: Build the model with all required layers and activation functions. 

Step8: Compile the model with optimizer.

Step9: Train the model mentioning the number of epoch.

Step10: Evaluate the model with input_ids and attention_mask. 

Step11: Print the accuracy on test data for the ImdB dataset and own small dataset. 

Step12: Get predictions from the model.
