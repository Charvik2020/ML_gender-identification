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
 <img src="https://github.com/Charvik2020/ML_gender-identification/blob/master/Report/Methodology.JPG" width="350"/>
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
<br>
 <img src="https://github.com/Charvik2020/ML_gender-identification/blob/master/Gabor%20algorithm/gabor.png" width="350"/>
<br>

- Face Detection Real Time 
<br>
 <img src="https://github.com/Charvik2020/ML_gender-identification/blob/master/Report/3.png" width="350"/>
<br>
<br>
 <img src="https://github.com/Charvik2020/ML_gender-identification/blob/master/Report/2.png" width="350"/>
<br>

- K-Means

<table class="tg">
  <tr>
    <th class="tg-yw4l">Gender</th>
    <th class="tg-yw4l">Error</th>
  </tr>
  <tr>
    <td class="tg-yw4l">Male</td>
    <td class="tg-yw4l">0.79</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Female</td>
    <td class="tg-yw4l">0.16</td>
  </tr>
</table>
Table-1 K-Means Error
<table class="tg">
  <tr>
    <th class="tg-yw4l">Class Label</th>
    <th class="tg-yw4l">Presision</th>
    <th class="tg-yw4l">Recall</th>
    <th class="tg-yw4l">F1-Score</th>
  </tr>
  <tr>
    <td class="tg-yw4l">Male</td>
    <td class="tg-yw4l">0.63</td>
    <td class="tg-yw4l">0.68</td>
    <td class="tg-yw4l">0.77</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Female</td>
    <td class="tg-yw4l">0.61</td>
    <td class="tg-yw4l">0.66</td>
    <td class="tg-yw4l">0.75</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Avg/Total</td>
    <td class="tg-yw4l">0.64</td>
    <td class="tg-yw4l">0.67</td>
    <td class="tg-yw4l">0.76</td>
  </tr>
</table>
Table-2 For Precision,Recall,F1 Score,Support


<table class="tg">
  <tr>
    <th class="tg-yw4l">Class Label</th>
    <th class="tg-yw4l">Male</th>
    <th class="tg-yw4l">Female</th>
  </tr>
  <tr>
    <td class="tg-yw4l">Male</td>
    <td class="tg-yw4l">40</td>
    <td class="tg-yw4l">160</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Female</td>
    <td class="tg-yw4l">15</td>
    <td class="tg-yw4l">78</td>
  </tr>
</table>
Table-3 Confusion Matrix


- SVM
<table class="tg">
  <tr>
    <th class="tg-yw4l">Gender</th>
    <th class="tg-yw4l">Error</th>
  </tr>
  <tr>
    <td class="tg-yw4l">Male</td>
    <td class="tg-yw4l">0.47</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Female</td>
    <td class="tg-yw4l">0.53</td>
  </tr>
</table>
Table-1 SVM Error
<table class="tg">
  <tr>
    <th class="tg-yw4l">Class Label</th>
    <th class="tg-yw4l">Presision</th>
    <th class="tg-yw4l">Recall</th>
    <th class="tg-yw4l">F1-Score</th>
  </tr>
  <tr>
    <td class="tg-yw4l">Male</td>
    <td class="tg-yw4l">0.88</td>
    <td class="tg-yw4l">0.88</td>
    <td class="tg-yw4l">0.88</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Female</td>
    <td class="tg-yw4l">0.74</td>
    <td class="tg-yw4l">0.75</td>
    <td class="tg-yw4l">0.743</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Avg/Total</td>
    <td class="tg-yw4l">0.81</td>
    <td class="tg-yw4l">0.81</td>
    <td class="tg-yw4l">0.81</td>
  </tr>
</table>

Table-2 For Precision,Recall,F1 Score,Support

<table class="tg">
  <tr>
    <th class="tg-yw4l">Class Label</th>
    <th class="tg-yw4l">Male</th>
    <th class="tg-yw4l">Female</th>
  </tr>
  <tr>
    <td class="tg-yw4l">Male</td>
    <td class="tg-yw4l">176</td>
    <td class="tg-yw4l">24</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Female</td>
    <td class="tg-yw4l">23</td>
    <td class="tg-yw4l">70</td>
  </tr>
</table>
Table-3 Confusion Matrix

- EigenFaces

<table class="tg">
  <tr>
    <th class="tg-yw4l">Gender</th>
    <th class="tg-yw4l">Error</th>
  </tr>
  <tr>
    <td class="tg-yw4l">Male</td>
    <td class="tg-yw4l">0.64</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Female</td>
    <td class="tg-yw4l">0.66</td>
  </tr>
</table>
Table-1 Eigenfaces Error

<table class="tg">
  <tr>
    <th class="tg-yw4l">Class Label</th>
    <th class="tg-yw4l">Presision</th>
    <th class="tg-yw4l">Recall</th>
    <th class="tg-yw4l">F1-Score</th>
  </tr>
  <tr>
    <td class="tg-yw4l">Male</td>
    <td class="tg-yw4l">0.73</td>
    <td class="tg-yw4l">0.20</td>
    <td class="tg-yw4l">0.313</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Female</td>
    <td class="tg-yw4l">0.33</td>
    <td class="tg-yw4l">0.84</td>
    <td class="tg-yw4l">0.47</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Avg/Total</td>
    <td class="tg-yw4l">0.53</td>
    <td class="tg-yw4l">0.52</td>
    <td class="tg-yw4l">0.39</td>
  </tr>
</table>
Table-2 For Precision,Recall,F1 Score,Support


<table class="tg">
  <tr>
    <th class="tg-yw4l">Class Label</th>
    <th class="tg-yw4l">Male</th>
    <th class="tg-yw4l">Female</th>
  </tr>
  <tr>
    <td class="tg-yw4l">Male</td>
    <td class="tg-yw4l">66</td>
    <td class="tg-yw4l">134</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Female</td>
    <td class="tg-yw4l">60</td>
    <td class="tg-yw4l">33</td>
  </tr>
</table>
Table-3 Confusion Matrix

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




