### Artificial Intelligence for the Media
# Gestures-Based Interaction


**Date:**  03/2021

**Link:** https://mimicproject.com/code/9f308a64-9d6a-d59f-81f8-a46b4f96fe9d

**Model:** BodyPix (MobileNetV1) - Given an image with one or more people, BodyPix's segmentPersonParts method predicts the 24 body part segmentations for all people. It returns a PartSegmentation object corresponding to body parts for each pixel for all people merged. 

**Tools:**  HTML / CSS / JavaScript | Learner.js | P5.js | Tensorflow.js

### Project
The aim of this project was to train a model that uses at least one feature transformation to achieve a type of interaction that isn’t possible (or easy) using raw features alone. This was done using an example in P5.js, BodyPix body part segmentation and Learner.js classifier. First, you need to consider what the purpose of the interaction should be and which body parts to include as an input for a classifier. I chose to use the left and right wrists and elbows. Then, you need to consider what feature transformation to use. I chose standard deviation for the neutral position as it reduces noise and ignores slight movements that occur even when you are still. I wanted to be able to move between positions without losing the connection to the class allocated to that gesture. Velocity was a good fit for the other gestures as it is well suited to movements that vary in speed.


***


### Reference

https://mimicproject.com/guides/learner

https://p5js.org/examples

https://p5js.org/reference/

https://p5js.org/learn/
