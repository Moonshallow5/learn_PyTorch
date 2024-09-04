# learn_PyTorch

## 🤔Introduction

This is a project from https://github.com/mrdbourke. 

I wanted to learn all about PyTorch, thus I completed this course in 3 weeks which allowed me to learn all sorts of things

## 💡What did I learn 

 ### In tutorial 3:
 * We imported data from **MNIST** and used matplotlib to print out the MNIST data.<br/> 
 * Implemented TinyVGG used to test the MNIST data <br/> 
 * Separated data into training and testing <br/> 
 * Built training and testing loops to run a couple epochs using a CPU and GPU and tried to see which one is faster<br/>
 * Learnt about suitable loss and optimizer functions <br/>
 * Implemented a Confusion Matrix<br/>
 * Extracted data from a Fahion MNIST dataset and tested it on a TinyVGG and used it to see how accurate the model is to determine the type of clothes there is<br/>

 ### In tutorial 4: <br/>
 * Learnt how to convert images into numPy arrays and also learnt how to resize images and convert it into tensors
 * Ran train and test loops with different number of epochs and saw what were the differences in terms of accuracy and time taken 
* Learnt about what num_workers mean
* Learnt about what HWC and CHW means
 

### In Tutorial 5: <br/> 

* Learnt how to write imprtant functions into separate files for future use<br/> 
* get_data.py was used to unzip the data files from the source
* data_setup.py was used to separate data into test and train
* engine.py was used for training and testing data
* model_builder.py is used to show the TinyVGG implementation
* utils.py is used to save the model


### In Tutorial 6: <br/>
* Learnt how to resize the training images, normalise it and convert it into tensors to be used by a pre-trained model 
* Learnt why we would need to freeze some sections of the model
* Learnt how to find the most wrong datasets and showed it onto a table from Pandas
* Plot graphs to see how close the train and test loss are close to each other and how close the train and test accuracy are

### In Tutorial 7: <br/>

* Learnt how to use Summary Writer, to save runs of a model
* Tested ml accuracy architecture of efficientnet_b2 and efficientnet_v2_s
* learnt how to use data augmentaton to achieve a larger variety of datasets to prevent overfiiting (which will be talked about later lol)

### In Tutorial 8: <br/>
* Learnt how to convert images into multiple patches
* Learn how to make a ViT architecture utiizing patch embedding, class tokens, positional embedding, Encoder layers and Mlp head
* Utilized a pretrained model called vit_b_16

### In Tutorial 9: <br/>
Revision of everything learnt above

## 🚧Challenges faced

Going trough this course and doing all the exercise in the notebook made me realised how hard learning ML is really like. Technically speaking, I went trough this whole course twice in order to get proper understanding on what's going on, and doing the exercises wasn't easy as well, it took me a really long time in order to understand the important algos that I saved into helper functions. But the more you practice, the better you going to be :)

