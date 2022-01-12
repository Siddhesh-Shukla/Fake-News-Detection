# Automated Fake News Detection
### Tri-BERT Siamese Model <br>
&nbsp;&nbsp;&nbsp;&nbsp; Siamese Network with 3 branches containing BERT as base architecture <br>

#### Dataset used: **LIAR PLUS** <br>

### Inputs <br>
&nbsp;&nbsp; **1st Branch** &nbsp;&nbsp;:&nbsp; News Statement <br>
&nbsp;&nbsp; **2nd Branch** :&nbsp; Justification <br>
&nbsp;&nbsp; **3rd Branch** &nbsp;:&nbsp; other columns from dataset such as author, source, etc
<br><br>
<img src="https://github.com/Siddhesh-Shukla/Fake-News-Detection/blob/main/Images/Model Diagram.png" width="1200"/> 

## Results
### 2-way classification: 
#### &nbsp;&nbsp; **Classes:** &nbsp; true, &nbsp; false
|               |               |
| :---          |          ---: |
| Precision     | 0.731676      |
| Recall        | 0.732439      |
| F1 Score      | 0.731924      |
| AUC-ROC Score | 0.726315      |
| Accuracy      | 73.2439%      |

### 6-way classification: 
#### &nbsp;&nbsp; **Classes:** &nbsp; true, &nbsp; mostly true, &nbsp; half true, &nbsp; barely true, &nbsp; false, &nbsp; pants on fire
|               |               |
| :---          |          ---: |
| Precision     | 0.329046      |
| Recall        | 0.342541      |
| F1 Score      | 0.291655      |
| AUC-ROC Score | 0.590121      |
| Accuracy      | 34.2541%      |
