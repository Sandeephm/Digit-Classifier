# Digit-Classifier

A convolutional network that predict hand written digits fromm 0 to 9. Tensorflow MNIST data set is used

Handwriting.py file is used for training. The model file got after training is present in model_v2.h5. Training is done for 10 epochs. To get a more accurate model, run for more than 10 epochs

To run the Handwriting.py file use the following command
```
python handwriting.py model.h5
```
![alt text](Model_train.PNG?raw=true)

Recognition.py files uses the trainned model.h5 files to predict handwritten digits. 

To run the recognition.py file use the following command
```
python recognition.py model.h5
```

![alt text](0.PNG?raw=true)

![alt text](1.PNG?raw=true)

![alt text](2.PNG?raw=true)

![alt text](3.PNG?raw=true)

![alt text](4.PNG?raw=true)

![alt text](5.PNG?raw=true)

![alt text](6.PNG?raw=true)

![alt text](7.PNG?raw=true)

![alt text](8.PNG?raw=true)

![alt text](9.PNG?raw=true)
