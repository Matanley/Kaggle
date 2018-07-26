# Kaggle

This is the first time I participate a Kaggle contest and is quite happy that I did this.

The reason for chosing this topic is it really is soving a real world problem (imagine if Uber self-driving cars had such a system mounted). My teamates and I participated in this contest mainly for learning and wanted to take it as a chance to practice what we had learnt. For this reason, the rank is not important at all and the process itself is the reward.

In building up the models, we chose to use Transfer learning and then focus on the finetuning and data augumentation procedures. After all, hardly can we build up a model from scratch which could surpass these famous architectures and their weights gained from Imagenet datasets.

For each part of the pipeline, I tried to use as many different methods as possible to see how each method perform. Here are some of the things I tried:

- Dataset split with sklearn VS Keras ImageDataGenerator

- Loss and accuracy checking with History.history VS Real time loss and accuracy tracking

- Model buiding with Sequential and Functional API

- Various data augumentation parameters and different top layers to see how the model perform

- Model ensemble for performance boost

I really enjoy the whole process (the training in AWS always give me a headache for my network issues) and may consider to participate more in the future. Thanks to my teamates Andy and Randy for their encouragement and helps along the way!

