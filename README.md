Project 1: Classify Images of Road Traffic Signs

This project is to train a model to classify images of European road traffic signs. You will be using a modified
version of the Belgium Traffic Sign Classification Benchmark. These are images of road traffic signs taken from
real-world vehicles. Note, this dataset, along with it's sister German TSC dataset, appear in many different
forms on various research and ML online resources. The data set for you to use in this assignment has been
specifically prepared for you, and is provided on Canvas.
The dataset consists of 28x28 gray-scale images and you are expected to use the dataset to perform two tasks:
• Classify images according to sign-shape, such as diamond, hex, rectangle, round, triangle.
• Classify images according to sign-type, such as stop, speed, warning, parking, etc.
Any over length content, or content outside of these requirements will not be marked. For example, if
you report is too long, ONLY the first 5 pages pages of text will be read and marked.
The key aspect of this assignment isn't your code or model, but the thought process behind your work.


5
RMIT Classification: Trusted
The correct classification of the images is given by the image sub-directories. Images are first sub-divided by
their shape, and then by their sign type. You should also note that some sign types have different individual
signs. For example, the speed-sign type has examples of signs of speeds from 10 - 70 mph. You are not required
to further sub-divide these signs, but consider all of the different signs as being of the sample type. Your tasks
is to investigate classifying the signs using both categories.
REQUIREMENTS
• You must investigate at least one supervised machine learning algorithms or each of the two categories
(Tasks). That is, you must build at least one model capable of classified the shape of the sign, and at least
one model capable of classifying the type of the sign.
• You are not required to use separate type(s) of machine learning algorithms, however, a thorough insti-
gations should consider different types of algorithms.
• You are required to ully train your own algorithms. You may not use pre-trained systems.
• You may NOT augment this data set with additional data.
• Your final report must conduct an analysis and comparison between classifying the two categories.
INDEPENDENT EVALUATION
• Your independent evaluation should consist of classifying images of traffic signs that you have collected.
You will need to either take your own digital photographs of traffic signs, and/or source suitable signs
from internet resources. You will need to process these images so they may be used with your trained
algorithms.
• As part of your evaluation, you should discuss challenges you face in combining this independent data and
your models.
