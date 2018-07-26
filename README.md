# Kaggle

This is the first time I participate a contest and is very happy that I did this.

The reason of chosing this topic is it really are soving a real world problems(imaging the Uber self-driving cars had such a system mounted). My teamates and I participate in this contest mainly for learning and want to take it as a chance to practice what we had learnt. For this reason, the rank is not important at all.

In building up the model, we chose to use Transfer learning and then focus on the finetuning and data augumentation procedures. After all, hardly can we build up a model from scratch which could surpass these famous architectures and their weights gained from Imagenet datasets.

For each part of the pipeline, I tried to use as many different methods as possible to see how each method perform. Things I tried:

- Dataset split with sklearn VS Keras ImageDataGenerator

- Loss and accuracy checking with History.history VS Real time loss and accuracy tracking

- Model buiding with Sequential and Functional API

- Various data augumentation parameters and different top layers to see how the model perform

- Model ensemble for performance boost

I really enjoy the whole process(only the training in AWS always give me a headache for my network issues) and may consider to participate more in the future. Thanks to my teamates Andy and Randy for their encouragement and helps along the way!

