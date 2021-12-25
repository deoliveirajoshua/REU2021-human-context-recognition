# REU2021-human-context-recognition

This project researches the efficacy of Controllable Generative Adversarial Networks (GANs) for human context recognition via mobile sensor data. Our goal is to develop novel generative architectures in order to predict a <i>target subject</i>'s missing sensor data for an activity based on patterns in data from other subjects that performed the same activity along with the <i>target subject</i>'s unique "style." The original respository can be found [here](https://github.com/deoliveirajoshua/REU2021-human-context-recognition).

## Exploring This Repository
### Dataset
All results found in this work are based on the University of California, Irvine's Human Activity Recognition Using Smartphones [Data Set](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones). The quality of our original data from the [The ExtraSensory Dataset](http://extrasensory.ucsd.edu/) was highly prone to user error, and its usage was thus discontinued. 
### Navigation
In */REU2021-human-context-recognition/UCI_data/models/*, we randomly select three subjects per group and attempt to replicate their activity data using our Controllable GAN. For each group of three, we perform feature selection and train our GAN in *UCI Unified Environment*, comparing its performance against the state-of-the-art GAN approach, indicated as *Solo GANs*. Each evaluation script is named with *A and S* or *A or S*, where the former signifies an evaluation of the GAN's ability to create realistic activity data that **also** matches up with the correct subject. The latter is the GAN's ability to create realistic activity and subject data **regardless of** whether the activity is paired up with the correct subject. Furthermore, in */REU2021-human-context-recognition/UCI_data/models/*, an ablation study was performed wherein the number of subjects to generate data for was increased. For each increase, our controllable GAN was compared against the state-of-the-art.

## Further Reading
If you would like to learn more about details such as our evaluation methodology or Controllable GAN architecture, be sure to check out our papers published at the 2021 IEEE International Conference on Big Data's 4th Special Session on Healthcare Data found [here](https://drive.google.com/file/d/1DRbJg9gq-dA9QIISikhy29rS3g6NhXst/view?usp=sharing), and the 2021 IEEE-MIT Undergraduate Research Technology Conference [here](https://drive.google.com/file/d/1mpfzsBY3csZtY3X-0Ytt1pSAaBvPlva8/view?usp=sharing).

## Project Members
<b>Faculty Advisor:</b> Elke Rundensteiner 
<br>
<b> PhD Mentor: </b>  Walter Gerych
<br>
<b> Research Members: </b> Joshua DeOliveira, Harrison Kim, MaryClare Martin
