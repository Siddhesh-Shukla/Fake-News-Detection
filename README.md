# Automated Fake News Detection
### Tri-BERT Siamese Model <br>
Siamese Network with 3 branches containing BERT as base model <br>
Dataset used: **LIAR PLUS** <br>
> **Inputs** <br>
> 1st Branch - News Statement <br>
> 2nd Branch - Justification <br>
> 3rd Branch - other columns from data such as author, source, etc
<br><br>
<img src="https://github.com/Siddhesh-Shukla/Fake-News-Detection/blob/main/Images/Model Diagram.png" width="1200"/> 

## Results
### 2-way classification: 
#### &nbsp;&nbsp; true, &nbsp;&nbsp; false
|               |               |
| :---          |          ---: |
| Precision     | 0.731676      |
| Recall        | 0.732439      |
| F1 Score      | 0.731924      |
| AUC-ROC Score | 0.726315      |
| Accuracy      | 73.2439%      |

### 6-way classification: 
#### &nbsp;&nbsp; true, &nbsp;&nbsp; mostly true, &nbsp;&nbsp; half true, &nbsp;&nbsp; barely true, &nbsp;&nbsp; false, &nbsp;&nbsp; pants on fire
|               |               |
| :---          |          ---: |
| Precision     | 0.329046      |
| Recall        | 0.342541      |
| F1 Score      | 0.291655      |
| AUC-ROC Score | 0.590121      |
| Accuracy      | 34.2541%      |
