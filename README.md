### Artificial Intelligence for the Media
# Assignment: Element 1: Practical Exam
Artificial Intelligence for the Media - Practical Exam


**Element 1:** Practical Exam open from 9am Monday 22/03/2021 - 9am Monday 29/03/2021

**Hand-in method:** Moodle Practical Exam. 1 attempt, open for 7 days to complete.

**Further Assessment information:** Practical exam: Task to be completed as per brief
***

### Exam Brief


In normal times, a practical exam would be taken in person and students would be given 2hrs to complete the given task. However, due to COVID-19 and blended learning, you are given no time limit and a single submission (as with the winter exams). However, this should give you a guide to how much time spend on the task.

We have provided a example sketch taken from the p5 site, with the boiler plate code for Learner.js included to take input from the MobileNet camera feature extractor. It will run fastest in Google Chrome.

https://mimicproject.com/code/9924b493-bcff-5325-5357-22226e91e1aa

Your task is to use a classifier with at least 6 classes to make an interactive sketch controlled by the model.

We have programmed the sketch to respond to the first 4 classes, it is up to you to edit the sketch to add in 2 more behaviours. You may also edit the 4 default mappings if you like, or switch to using a regression model if you would like to make continuous mappings (in which case you should use a minimum of 6 outputs).


#### Controls

Class 0 - stay still
Class 1 - rotate clockwise
Class 2 - rotate anti - clockwise
Class 3 - move forwards
Class 4 - ?
Class 5 - ?

To edit the code, you will need to sign in, and fork the document


When designing extra behaviours you can consider shape, colour, speed, direction (too name a few!). See links to p5 reference below as an aid.


#### Building a model

As well as programming the extra 2 behaviours, you should also pick 6 classes / mappings, record in a dataset and train the model.

When picking your classes / mappings and building your dataset, you should consider

1. How well they work well for controlling the sketch and your creative aims
2. How well they work for building an accurate model


Practise Mappings without Camera Input

You can simulate the model control using the Learner.js interface using:

* The dropdown menu for classifiers
* The sliders for the regression models

It is likely you will have to iterate between designing your interactions and inputs and building your datasets to reach a successful sketch


#### Submit

A Link to a GitHub repo containing:

1. A link to your mimic project
2. A video of you using your sketch (2-3 min, phone film or screen capture is fine, should include explanation and demonstration of all of your classes / mappings). *
3. Your dataset (.json file, click “Download data” on Learner.js GUI)
4. Text file with question responses (below)

*Screen Record in Quicktime on Mac, Screen Record on Windows 10

Make sure your GitHub project is private, with lmccallum added as a Collaborator. Find instructions here

#### Questions

1. How well does your controller work (with reference to all 6 classes)?
2. Why did you choose these classes / mappings? Consider how MobileNet represents the camera input, model performance, transitions between classes and their relation to the interaction in the sketch in this response.
3. What were your tactics for improving your model’s performance?
4. What was the biggest challenge when completing this task?
5. How has using machine learning benefitted or obstructed your development the interactivity in this sketch?


#### Reference

Lectures 1.1, 1.2, 2.2., 3.1

https://mimicproject.com/guides/learner

https://p5js.org/examples
https://p5js.org/reference/
https://p5js.org/learn/


#### Learning Outcomes being assessed by Exam

LO2 Understand and use ML fundamental concepts such as classification and regression in both real and non-real time. (Knowledge, Process, Realisation)

LO3 Create, test and deploy ML systems for problem solving (Gesture, Image, Sound, Video and Graphics) (Knowledge, Realisation)


#### Rubric

With reference to the above learning outcomes, students will be assessed on

* Their customisation of the project to fit controller

* Their ability to build an accurate model over at least 6 different classes, and the appropriateness of input to output mapping.

* Challenge and complexity of the poses picked for classification

* Quality of reflection of the training and modelling process in relation to creative goals and input medium



