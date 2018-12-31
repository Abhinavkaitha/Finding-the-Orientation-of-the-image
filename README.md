Kindly check the the pdf files for detailed report.

Our best model is KNN so, the output of KNN and best is same. So, we uploaded only KNN output(no best output file).

We have double checked the model files and output files. If there is any error, kindly train the models again. It wont take much time.

KNN - No training, So training data is stored in model file and used as training data while testing.

Adaboost - less than 90 seconds for training.

Decision Forest - 21 minutes for training.

For Training

./orient.py train train-data.txt nearest_model.txt nearest

./orient.py train train-data.txt adaboost_model.txt adaboost

./orient.py train train-data.txt forest_model.txt forest

./orient.py train train-data.txt best_model.txt best

For Testing

./orient.py test test-data.txt nearest_model.txt nearest

./orient.py test test-data.txt adaboost_model.txt adaboost

./orient.py test test-data.txt forest_model.txt forest

./orient.py test test-data.txt best_model.txt best

Output Files

output_nearest.txt

output_adaboost.txt

output_forest.txt
