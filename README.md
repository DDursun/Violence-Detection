# Violence-Detection

This repository is dedicated to the research paper titled "Comparative Analysis: Violence Recognition from Videos using Transfer Learning". All the related, processing, model training, and testing notebooks will be added soon.


## Dataset

The data utilized in the training and prediction are called “Real life Violence Situations Dataset” [1]. The total size of the dataset is ~2 GB. The dataset consists of 2000 videos with an even split between violent and nonviolent classes (1000 violent and 1000 nonviolent videos). The videos that are labeled as “violent” contain street fights and fights in crowds in several environments and conditions. The videos labeled as nonviolent contain daily life situations including sports, eating, scenes from movies, and casual conversations between individuals. This dataset is considered to be more complex compared to other well-known datasets used to solve this problem. The videos have different characteristics in terms of camera angle, lighting conditions, resolution, and frame rate. In Fig. 1, two videos from the dataset are visualized. The difference in aforementioned characteristics can be easily seen through rows of the visual. Also, the video footages vary significantly in their content. These differences imitate realistic scenarios. Hence, forming a challenge in terms of well-generalized and accurate model building.

For ease of usage, data has been updated to the drive. It can easily be loaded to any notebook directly from the Kaggle:
https://www.kaggle.com/datasets/mohamedmustafa/real-life-violence-situations-dataset/data



# References

1. M. Soliman, M. Kamal, M. Nashed, Y. Mostafa, B. Chawky, D. Khattab, “ Violence Recognition from Videos using Deep Learning Techniques”, Proc. 9th International Conference on Intelligent Computing and Information Systems (ICICIS'19), Cairo, pp. 79-84, 2019
