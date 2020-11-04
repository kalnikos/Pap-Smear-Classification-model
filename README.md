# Pap-Smear-Classification

The goal of this project is to develop a classification model that will be able to identify the cervical dysplasia in two main categories, normal and abnormal. The data set that I’mworking on has a target divided into 7 categories depending on how serious the dysplasia is. In order to divide these categories I will try to implement two unsupervised methods aiming to find:
1.	The number of the clusters. 

2.	How I would split up these clusters.

In addition,I will  implement some techniques to determine highly correlated features and a dimension reduction method in order to identify patterns and divide the target column into less categories. 

My data has 26 features and 500 rows. Although I have to deal with many features the number of the rows is not so big and this is something that I will try to increase in order to develop another model and compare the results.Firstly, I used some statistics techniques to examine the distribution of the features and scatterplots aiming to find which variables are having high correlation.

![cor](https://user-images.githubusercontent.com/66875726/97926634-21763300-1d6c-11eb-91ff-4ba6dbc76721.png

Yes I know is a little bit chaotic, many features but after I used the Univariate Feature Selection method and I have to manage 15 features. 

![Χωρίς τίτλο](https://user-images.githubusercontent.com/66875726/97927626-04426400-1d6e-11eb-93c0-4b0e1c55659e.png)

After these steps I implemented two Unsupervised techniques in order to determine the number of the classes that I could split the data. I started with a Hierarchical algorithm and below is the dendrogram of the algorithm.   

![dend](https://user-images.githubusercontent.com/66875726/97928272-5a63d700-1d6f-11eb-8c35-62264709abce.png)

As we can see from the dendrogram I can split the data into 2 or 3 classes, Definitely is an improvement considering the seven classes that the target group is distinguish.
The second step that it was really useful to determine the distribution of the data were some scatter plots that show the correlation of the feature with the target group, compared data divided into 2 and 3 categories.


| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
|  ![kerne_shot_2](https://user-images.githubusercontent.com/66875726/98175037-88c3ec80-1efe-11eb-8ac5-055d3f625522.png)   | ![kyto_short_2](https://user-images.githubusercontent.com/66875726/98175055-91b4be00-1efe-11eb-8a57-440330ee6cf5.png)     |  ![cyto_long_2](https://user-images.githubusercontent.com/66875726/98175084-9c6f5300-1efe-11eb-9e84-9e054936e671.png)
  


| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
|  ![Cyto_short_3](https://user-images.githubusercontent.com/66875726/98175102-a5602480-1efe-11eb-8c4b-34727d4d37e6.png)
   | ![kerne_shot_3](https://user-images.githubusercontent.com/66875726/98175129-af822300-1efe-11eb-95c3-17868aa802e4.png) 
      | ![kyto_long_3](https://user-images.githubusercontent.com/66875726/98175149-b6109a80-1efe-11eb-8cb6-b22e0cc019da.png)
      |









