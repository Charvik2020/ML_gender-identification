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
![Image](https://github.com/Charvik2020/ML_gender-identification/raw/master/Report/Methodology.JPG)
    
## Requirements
- Python 2.7+
- Anaconda
- OpenCV
## Dataset Requirement
- Labeled Dataset (Ex. 01_m for male and 02_f for female)
- Dimension 48 x 48 pixel

## Output

- K-Means

<table class="tg">
  <tr>
    <th class="tg-yw4l">Gender</th>
    <th class="tg-yw4l">Error</th>
  </tr>
  <tr>
    <td class="tg-yw4l">Male</td>
    <td class="tg-yw4l">0.17</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Female</td>
    <td class="tg-yw4l">0.82</td>
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
    <td class="tg-yw4l">0.68</td>
    <td class="tg-yw4l">0.82</td>
    <td class="tg-yw4l">0.74</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Female</td>
    <td class="tg-yw4l">0.31</td>
    <td class="tg-yw4l">0.17</td>
    <td class="tg-yw4l">0.22</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Avg/Total</td>
    <td class="tg-yw4l">0.49</td>
    <td class="tg-yw4l">0.49</td>
    <td class="tg-yw4l">0.48</td>
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
    <td class="tg-yw4l">164</td>
    <td class="tg-yw4l">36</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Female</td>
    <td class="tg-yw4l">77</td>
    <td class="tg-yw4l">16</td>
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
    <td class="tg-yw4l">0.19</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Female</td>
    <td class="tg-yw4l">0.48</td>
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
    <td class="tg-yw4l">0.78</td>
    <td class="tg-yw4l">0.81</td>
    <td class="tg-yw4l">0.79</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Female</td>
    <td class="tg-yw4l">0.56</td>
    <td class="tg-yw4l">0.52</td>
    <td class="tg-yw4l">0.54</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Avg/Total</td>
    <td class="tg-yw4l">0.67</td>
    <td class="tg-yw4l">0.66</td>
    <td class="tg-yw4l">0.66</td>
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
    <td class="tg-yw4l">160</td>
    <td class="tg-yw4l">38</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Female</td>
    <td class="tg-yw4l">45</td>
    <td class="tg-yw4l">49</td>
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
    <td class="tg-yw4l">0.28</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Female</td>
    <td class="tg-yw4l">0.76</td>
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
    <td class="tg-yw4l">0.67</td>
    <td class="tg-yw4l">0.72</td>
    <td class="tg-yw4l">0.69</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Female</td>
    <td class="tg-yw4l">0.29</td>
    <td class="tg-yw4l">0.25</td>
    <td class="tg-yw4l">0.268</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Avg/Total</td>
    <td class="tg-yw4l">0.48</td>
    <td class="tg-yw4l">0.485</td>
    <td class="tg-yw4l">0.48</td>
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
    <td class="tg-yw4l">144</td>
    <td class="tg-yw4l">56</td>
  </tr>
  <tr>
    <td class="tg-yw4l">Female</td>
    <td class="tg-yw4l">70</td>
    <td class="tg-yw4l">23</td>
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




