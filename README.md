# emotion_classify
Learn emotion classification by practice and follow tutorials. 
The ultimate idea of this repo is to see if humans have developed a better understanding of emotion through facial features since LeBrun. 
LeBrun is a famous artist who explored emotion in his paintings. He embedded the emotions on the face. 
Another inspiration is "Can Machine Perceives Emotion" (https://youtu.be/7uhhM3UyHvc). I am looking forward to test if humans have any improvement.


- pick a [fine-art dataset](https://www.kaggle.com/momanyc/museum-collection)
- run Detectron2 on the dataset to select person instance in the images, and save the segment masks in a file
- manually label facial expression follow the AFFNET format
- choose several state-of-arts emotion classification models to compare the results
