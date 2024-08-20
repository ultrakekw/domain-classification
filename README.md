# domain-classification
Description of the task from the customer:  
Develop a machine learning system that predicts by writing a domain whether this domain is a DGA domain created by the algorithm. The generated domains are used by malware authors to manage infected computers (they cannot register and use one domain because this domain will be blocked, so malware, depending on the date, refers to a specific generated domain that the author registers to manage computers on that date).
Two samples are provided to complete the task: validation (val.csv) and verification (test.csv). The samples are presented as csv files with the domain column - the domain itself, and for validation – is_dga – whether this domain is generated: 1=yes, 0=no.
On the validation sample, it is required to calculate the accuracy characteristics and write them to a text file validation.txt with the following content (changing the values to yours):  
True positive: 2  
False positive: 20  
False negative: 18  
True negative: 60  
Accuracy: 0.6200  
Precision: 0.0909  
Recall: 0.1000  
F1: 0.0952  

For the verification sample, you need to create a prediction.csv file with two columns – domain and is_dga, which will contain a prediction for each domain of the verification sample, in the same order.
