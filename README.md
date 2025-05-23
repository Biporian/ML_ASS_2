Newly Generated Features:
1. Run './image_flat/flattened_images_test.ipynb' and './image_flat/flattened_images.ipynb' (this will generate a large number of image files in directory)
2. Run './dig_feature/ocr_digit_detection_test.ipynb' and './dig_feature/ocr_digit_detection.ipynb'
3. Run './CNN_feature/cnn_feature_test.ipynb' and './CNN_feature/cnn_feature.ipynb'

Run Neural Network Model:
1. Run './NN/neuralcnn.ipynb'
2. This will generate a csv called './NN/resultscnn.csv' - this is the desired Kaggle results file

Run SVM, LOGREG, RF models on given features:
1. Run titular file jupyter notebook file 
2. Cell at the end will generate a csv with a corresponding name ending in 'outcome':
    i.e., "svm_initial_outcome.csv"

Run SVM, LOGREG, RF models on all features:
1. Go to runeverything.ipynb
2. The models are in cells in order, at the bottom of the file are cells to generate the outcome, named:
    e.g., "svm_alldata_outcome.csv"

 
 ##### Some of the models were saved using pkl files, and random lines of code exist throughout
 ##### the submission loading them. These need to be commented out/ignored if not relevant to current task
