# Siamese-Networks

### Standard Classification vs. One Shot Classification
- Standard classification is what nearly all classification models use. The input is fed into a series of layers, and in the end , the class probabilities are output. If you want to predict dogs from cats, you train the model on similar(but not same) dogs/cats pictures that you would expect during prediction time. Naturally, this requires that you have a dataset that is similar to what you would expect once you use the model for prediction.
- One Shot Classification models, on the other hand, requires that you have just one training example of each class you want to predict on. The model is still trained on several instances, but they only have to be in the similar domain as your training example.
