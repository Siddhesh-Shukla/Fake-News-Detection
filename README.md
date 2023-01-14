# Automated Fake News Detection
### Tri-BERT Siamese Model <br>
&nbsp;&nbsp;&nbsp;&nbsp; Siamese Network with 3 branches containing BERT as base architecture <br>

#### Dataset: [LIAR-PLUS](https://github.com/Tariq60/LIAR-PLUS)

### Inputs <br>
&nbsp;&nbsp; **1st Branch** &nbsp;&nbsp;:&nbsp; News Statement <br>
&nbsp;&nbsp; **2nd Branch** :&nbsp; Justification <br>
&nbsp;&nbsp; **3rd Branch** &nbsp;:&nbsp; other columns from dataset such as author, source, etc
<br><br>
<img src="https://github.com/Siddhesh-Shukla/Fake-News-Detection/blob/main/Images/Model Diagram.png" width="1200"/> 

## Results
### 2-way classification: 
#### Classes
```
1. True
2. False
```

|               |               |
| :---          |          ---: |
| Precision     | 0.731676      |
| Recall        | 0.732439      |
| F1 Score      | 0.731924      |
| AUC-ROC Score | 0.726315      |
| Accuracy      | 73.2439%      |

### 6-way classification: 
#### Classes 
```
1. True
2. Mostly true
3. Half true
4. Barely true
5. False
6. Pants on fire
```
|               |               |
| :---          |          ---: |
| Precision     | 0.329046      |
| Recall        | 0.342541      |
| F1 Score      | 0.291655      |
| AUC-ROC Score | 0.590121      |
| Accuracy      | 34.2541%      |
