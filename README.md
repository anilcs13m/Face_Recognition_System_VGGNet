# Face Recognition System VGGNet
creating a face recognition system from scratch using caffe deep learning library, dataset we are using in this face recognition system is from vgg face dataset.

# All the steps to create Face Recognition System 
## step 1:- Data Download

### Download vgg face data set 
Here are the steps for downloading vgg face dataset


### Download data from google image search
using this python script you can download images from google image search just you have to add names for person sarch in the cel.txt file, the images downloaded from google search contain some wrong face or different images, so more preprocessing
is required.

## step 2:- Data Preprocessing
### Croping Image
we are cropping image according to vgg net input[224 * 224]
### Creating LMDB data
caffe take a specific format of data input

## step 3: Model Fine Tuning
take pre-training model, here are the steps to do fine tuning

## step 4: Model Tesing 
this python script run for tesing model

## step 5: Final Model Deploment
Final deploment
