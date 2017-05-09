## Project Title
Gender Identification

## Member Group - 7
- Anuj Shah-1401084
- Aatman Dholakia-1401013
- Charvik Patel-1401079
- Rajat Barot-1401045

## Mentor's And Teaching Assistant
- Dr. Mehul raval
- Shashwat Sanghvi(TA) 
- Sharvil Shah(TA)


## Idea

Gender Identification has become area of extensive research
due to it’s increasingly powerful applications. Moreover augmenting
it in real time scenario can be useful in many applications
in many fields. A successful gender classification could
have great impact in improving human computer interactions.
Practically it is imperative to improve the algorithms from time
to time in order to achieve higher accuracy levels and build
more accurate and robust systems. 

## Methodology
<br>
 <img src="https://raw.githubusercontent.com/Charvik2020/ML_gender-identification/blob/master/Report/Methodology.JPG" width="350"/>
<br>

## Requirements
- Python 2.7+
- Anaconda
- OpenCV
## Dataset Requirement
- Labeled Dataset (Ex. 01_m for male and 02_f for female)
- Dimension 48 x 48 pixel

## Output
- Gabor Algorithm Output
![My image](https://github.com/Charvik2020/ML_gender-identification/blob/master/Gabor%20algorithm/gabor.png)

- Face Detection Real Time 
<br>
 <img src="https://github.com/Charvik2020/ML_gender-identification/blob/master/Report/3.png" width="350"/>
<br>
<br>
 <img src="https://github.com/Charvik2020/ML_gender-identification/blob/master/Report/2.png" width="350"/>
<br>

- K-Means
Table-1 K-means Error
| Gender        |     Error     |
| ------------- | ------------- |
| Male          | 0.79          |
| Female        | 0.16          |

Table-2 For Precision,Recall,F1 Score,Support
| Class Label   |    Precision  | Recall      |  F1-Score  |
| ------------- | ------------- | ------------| ---------- |
| Male          | 0.63          |0.68         |0.77        |
| Female        | 0.61          |0.66         |0.75        |
| AVG/Total     | 0.64          |0.67         |0.76        |

Table-3 Confusion Matrix
| Class Label   |    Male       | Female      | 
| ------------- | ------------- | ------------| 
| Male          | 40            |160          |
| Female        | 15            |78           |

- SVM
Table-1 SVM Error
| Gender        |     Error     |
| ------------- | ------------- |
| Male          | 0.47          |
| Female        | 0.53          |

Table-2 For Precision,Recall,F1 Score,Support
| Class Label   |    Precision  | Recall      |  F1-Score  |
| ------------- | ------------- | ------------| ---------- |
| Male          | 0.88          |0.88         |0.88        |
| Female        | 0.74          |0.75         |0.743       |
| AVG/Total     | 0.81          |0.81         |0.81        |

Table-3 Confusion Matrix
| Class Label   |    Male       | Female      | 
| ------------- | ------------- | ------------| 
| Male          | 176           |24           |
| Female        | 23            |70           |

- EigenFaces
Table-1 EigenFaces Error
| Gender        |     Error     |
| ------------- | ------------- |
| Male          | 0.64          |
| Female        | 0.66          |

Table-2 For Precision,Recall,F1 Score,Support
| Class Label   |    Precision  | Recall      |  F1-Score  |
| ------------- | ------------- | ------------| ---------- |
| Male          | 0.73          |0.20         |0.313       |
| Female        | 0.33          |0.84         |0.47        |
| AVG/Total     | 0.53          |0.52         |0.39        |

Table-3 Confusion Matrix
| Class Label   |    Male       | Female      | 
| ------------- | ------------- | ------------| 
| Male          | 66            |134          |
| Female        | 60            |33           |

## Conclusion
For the Proper Gender Identification we need to Detect
the face and need to detect the skin color,facial feature
extraction,Geometric Distance between Extracted Feature and
need to classify data into two class as follow
- Male
- Female
# Eigenfaces
- Advantages:the algorithm is basically identifying almost every new face to be male, hence contributing to the large error for females.
- Disadvantages:it cannot give you an intuitive sense of why the algorithm is favouring males. But upon looking at the data where the algorithm misclassified the person, we conclude that female subjects who have short hair, hair tied back or in a scarf were almost always labeled male. Having insufficient examples for them to train on might have resulted in this outcome.
# K-Means
- Advantages:Faster then EigenFaces if variable are huge
- Disadvantages:Running time is too slow since it compute distance between each of the k nearest point
# SVM
- Advantages: Computationally better then Eigenfaces and K-Means
- Disadvantages:When Dimension are very high then SVM result into large in-accuracy.




