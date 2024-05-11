# Adversarial-Exemples-in-Computer-Vision

### Description
In this repo you can find all ressources used within the **"Fooling Ai image classifiers"** projects .\
The goal of this project is to study how weak AI image classifiers are against adversarial attacks.

### Abstract
Often , when building an AI image classifier ,we
tend to evaluate the resulted model by measuring its accuracy on
the test-set . However is this approach enough ? In this paper we
tested the ability of MobileNetV2 to correctly classify carefully
generated adversarial examples to harm the model .We observed
it’s weakness in all tests we did .Which leads as to the need to
evaluate this kind of AI models taking in consideration this type
of input images.

### Experiments 

- Experiment 1 : apply the Fast Gradiant Sign Method **FGSM** technique to generate noise that fools our model ( MobileNetV2 )
- Experiment : trying to get best of FGSM by tweaking values of the intensity of genrated noise
- Experiment 3 : optimizing the FGSM formula by applying adaptive amount of noise according to each pixel influence on the model's prediction 
- Experiment 4 : Test the accuracy of the model on Printed 🖨️ and Photographed 📷 adversarial images


### Links
[Project Report link](Fooling%20AI%20Image%20Classifiers.pdf)\
[Project Notebook](Fooling_AI_image_Classifiers.ipynb)\
[LinkedIn post link](https://www.linkedin.com/posts/ossama-outmani_adversarial-examples-on-image-classifiers-activity-7183191847349997568-BvL3?utm_source=share&utm_medium=member_desktop)

### Author
Outmani Ossama

