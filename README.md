# Food_Classifier

### Model
I used transfer learning to obtain better results. The model I used is EfficientNetV2L (trained on the ImageNet dataset).

`accuracy: 0.9950 - loss: 0.1130 - val_accuracy: 0.9531 - val_loss: 3.4628`


### Libraries

This project requires the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [matplotlib](http://matplotlib.org/)
- [pandas](https://pandas.pydata.org/)
- [tensorflow](https://www.tensorflow.org/)
- [Keras - Sequential Model](https://keras.io/guides/sequential_model/)
- [os](https://docs.python.org/3/library/os.html)
- [random](https://docs.python.org/3/library/random.html)
- [pathlib](https://docs.python.org/3/library/pathlib.html)
- [sklearn](https://scikit-learn.org/stable/)
- [pickle](https://docs.python.org/3/library/pickle.html)


### Code

Code is provided in the `food` notebook file.


### Data

Data is imported from google drive.

3 Classes: `apple_pie`, `hamburger`, `pizza`
