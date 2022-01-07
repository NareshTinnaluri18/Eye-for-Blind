# Eye-for-Blind

[eye for blind pdf.pdf](https://github.com/NareshTinnaluri18/Eye-for-Blind/files/7827691/eye.for.blind.pdf.pdf)


Eye for Blind
Problem Statement Overview
Today, in the world of social media, millions of images are uploaded daily. Some of them are about your friends and family, while some of them are about nature and its beauty. Imagine a condition where you are not able to see and enjoy these images — a problem that blind people face on a daily basis. According to the World Health Organization (WHO), it has been reported that there are around 285 million visually impaired people worldwide and out of these 285 million, 39 million are totally blind. 

 

In an initiative to help such people experience the beauty of the images, Facebook had earlier launched a unique feature that can help blind people operate their app on their respective mobile phones and the feature would explain to the blind person the contents of an image that their friends have posted on Facebook. So, say, if someone posted a picture with their dog in the park, the application would speak out the contents and may describe it like, “This image may contain a dog standing with a man around the trees.”

 

In this module, you will understand how a blind person can overcome all these problems and go along with ordinary people when it comes to seeing. You will learn how to make a model similar to what Facebook made, specifically making the blind person know the contents of an image in front of them with a CNN-RNN based model. The model will convert the contents of an image and will give the output in the form of audio.

 

In this project, you will be converting the image to text description first and then using a simple text to speech API, the extracted text description/caption will be converted to audio. So the central part of this capstone is focused on building the caption/text description as the second part, which is transforming the text to speech is relatively easy with the text to speech API. Once the model is built, you will deploy the project on your local system using a Flask based model to generate audio-based content for any image.

 



Representation of the entire project flow

 

Industry & Function
Computer Vision

Image captioning

Text to Speech

Capstone Breakdown
Specialised Content Duration: ~2 Weeks
Project Duration: ~2 Weeks
 

Specialised Content:

When you observe certain information such as an image or text, you can focus on the important areas needed while ignoring the unnecessary portion instead of focusing on all the given data. This kind of task seems very easy for our human intelligence because we can do it effortlessly, but when we need to make a model that does the same task, it would require quite a complex architecture. 

Over the years, researchers have tried to build complex vision models that we humans can see. The model that you will make is based on the attention mechanism, which simulates how we perceive visual information through complex cognitive ability. To focus on essential and ignore areas, such kind of spatial understanding is the core principle of attention mechanism. Originally the attention mechanism was designed to improve language models, but you will use it for image models to generate text description in this capstone. You will use the spatial feature of the attention mechanism inside an Encoder-Decoder architecture to visualise which areas of the image our model focuses on as it generates the text description or caption of the image.




A sample of the output text using the Attention mechanism

 

This capstone is majorly focused on skill enhancement and has little to do with respect to any business context. The specialised content covered is relatively difficult with respect to other capstones as you have to build a custom model to implement the Attention model with Encoder-Decoder architecture. Therefore while choosing this capstone, it is advised that one should be comfortable with the workings of CNN & RNN.

Attention models are not part of Keras' built-in model; therefore, you need to create a custom model. To create a custom model, you need to know the concepts behind the Subclassing API, which will also be covered in the specialised content modules.

 

Capstone rigour & expectations
Covering the specialised content will take nearly two weeks; and post that you will have two weeks to complete your capstone project using the newly learnt concepts. Therefore, once you have selected this capstone, you will have to be on your toes right from the start to have comfortability while attempting the project. Ideally, you will have to dedicate around 15-20 hours to grasp the given concepts fully.
 

Prerequisites
Understanding how RNN works is a prerequisite for this session. 

 

Skills tested in this capstone
For a broader understanding, here is the list of topics that will be included in the capstones:

CNN-RNN based architecture
Attention model
Greedy vs beam search
Bleu score
Custom model building using Tensorflow
Data preparation using Tensorflow
