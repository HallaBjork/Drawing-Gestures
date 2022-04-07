### Artificial Intelligence for the Media
# Gestures-Based Interaction


**Date:**  03/2021

**Link:** https://mimicproject.com/code/9f308a64-9d6a-d59f-81f8-a46b4f96fe9d


### Project
Using this example of project as a starting point, train a model that uses at least one feature transformation to achieve a type of interaction that isn’t possible (or easy) using raw features alone. You should consider which body parts to include, what features to use on them, and the size of the window to use.You can select which body parts are input to the model by adding them to the bodyParts array in the learner tab.Really matters how do you set up your problem and the sample you gave defines the world of your model.
You should consider which body parts to include, what features to use on them, and the size of the window to use.

I chose to use the left and right wrists and elbows to create input for a classifier. As for feature transformation I chose Standard Deviation for the neutral position (class 0) and Velocity for the hand gestures (classes 1 and 2).

The reason I chose the wrists was for the waving motions. However, through trial and error I found that using the elbows was necessary as they are also used for the waving gesture. Using them I was able to get a more accurate classifier. I chose Standard Deviation features for the neutral position as it reduces noise and ignores slight movements that occur even when you are sat still. Velocity was a good fit for the other gesture as it is well suited to movements that vary in speed. Since I wanted to be able to move between positions without losing the connection to the class allocated to that gesture, I found that using these features worked much better than using raw features.


This body tracker works faster in Chrome

#### Reference

https://mimicproject.com/guides/learner
https://p5js.org/examples
https://p5js.org/reference/
https://p5js.org/learn/
