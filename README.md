# Drug-using-analysis

[Why do we need to conduct a medication rationality analysis?]

1. Want to know if the wrong medicine was prescribed to the patient --> A laxative was prescribed to a patient with headache symptoms?
2. Currently, manual inspection is used to determine whether the medication is correct --> Thousands of diseases require manual judgment, which is time-consuming and labor-intensive.

[How to help hospitals?]

It is hoped that through data mining, drugs that may be used for various diseases can be found from historical prescription data, thereby establishing rules to help hospitals reduce manual inspection costs.

[Data analysis process:]
a. Data format cleaning [1]
b. Data observation
c. one-hot-encoding
d. Find rules through Apriori algorithm
e. Confirm the rationality of the rules with the pharmacist
f. Adjust the Apriori threshold
g. Rule establishment


The original historical prescription data is like this:
![image](https://github.com/hihinick/Drug-using-analysis/assets/86997964/9d2d208b-a705-48d5-a617-6a8074068efe)

Filter the columns of original data.
![image](https://github.com/hihinick/Drug-using-analysis/assets/86997964/03bdc6b1-c877-4050-a3e4-f73bfdcd0542)

Transfer data format and encode the data to the input format of Apriori algorithm.
![image](https://github.com/hihinick/Drug-using-analysis/assets/86997964/62dafbcf-59a8-43ce-9378-1f912cf1efee)


Review the rules:

Frequent item sets for each disease.
![image](https://github.com/hihinick/Drug-using-analysis/assets/86997964/c8ca1f26-0f9e-4b69-8baa-55f257fd7fa5)

Frequent item visualization.
![image](https://github.com/hihinick/Drug-using-analysis/assets/86997964/af6cb0f5-4d41-4e9b-912a-dc1941e76ed9)



