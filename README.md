# Drug-using-analysis

[Why do we need to conduct a medication rationality analysis?]

1. Want to know if the wrong medicine was prescribed to the patient --> A laxative was prescribed to a patient with headache symptoms?
2. Currently, manual inspection is used to determine whether the medication is correct --> Thousands of diseases require manual judgment, which is time-consuming and labor-intensive.

[How to help hospitals?]

It is hoped that through data mining, drugs that may be used for various diseases can be found from historical prescription data, thereby establishing rules to help hospitals reduce manual inspection costs.

[Data analysis process:]
Historical prescription data --> Data format cleaning --> one-hot-encoding --> Apriori --> Confirm the rationality of the rules with the pharmacist --> Adjust the apriori threshold --> Rule establishment
1. Historical prescription data
2. Data format cleaning
3. one-hot-encoding
4. Apriori
5. Confirm the rationality of the rules with the pharmacist
6. Adjust the Apriori threshold
7. Rule establishment


The original data is like this:
![image](https://github.com/hihinick/Drug-using-analysis/assets/86997964/9d2d208b-a705-48d5-a617-6a8074068efe)



