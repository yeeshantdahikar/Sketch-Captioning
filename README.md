# Sketch Captioning using LSTM and BiLSTM

Captioning for sketch sceneries is a challenging task in computer vision (CV) and natural language processing (NLP). 
It entails creating captions with specific details for sketches of settings, things, or actions. Deep learning-based techniques have produced 
encouraging achievements in this area in past few years. Recent years have seen a lot of studies on the use of artificial intelligence (AI) 
to produce captions for images and sketches. The volume of generated captions was constrained, similarly to the length of these short captions. 
There is a lot of research done by researchers on image captioning but sketch scene captioning is new research work on which research can be done.

Sketch Captioning using LSTM and BILSTM. This research presents an unsupervised deep learning-based framework that combines an encoder-decoder model and 
a recurrent neural network (RNN) structures like Long Short Term Memory (LSTM) and Bidirectional Long Short Term Memory (BiLSTM) to create caption for particular sketch scene. 
Basically paper is providing the comparision of accuracies of LSTM and BiLSTM models with the help of bilingual evaluation understudy (BLEU) score 
while using the dataset named as flickr8k.

Although the current results appear promising, it is challenging to make assumptions on the full accuracy of the fully trained model because this work has not yet been fully trained. However, this does not imply that we do not have a clever understanding of what model needs and how we can improve the performance.

From this research, we know that the captions can be generated from the sketch scenes with the help of LSTM and BiLSTM models. The performance of the models can be increased by increasing the number of epochs. In this work, we used maximum 20 epochs and model giving good result. 


We have taken the Flickr8k dataset to train our model which contains images with 5 captions which is not preferable to get captions for sketchy scenes. There are no such datasets which contains sketch scenes. Most of the dataset available contains sketches of single objects instead of sketch scenes. If we able to train the model on the dataset having the sketch scenes with the captions then model can able to give the more accurate output on sketchy scenes.

The BLEU scores supported in distinguishing the performance of the models. Though both models giving good output but by seeing the BLEU scores and generated captions, we can say BiLSTM model perform better than LSTM model. The models can perform even better if we used proper dataset and apply preprocessing on the dataset in proper way. This work can be beneficial for a number of applications, including graphical user interface, education, computer art such as paintings, cartoon drawing, logo design.

