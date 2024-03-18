# Default-of-credit-card-clients-Prediction
Building a SupportVectorMachine algorithm aimed at the case of customers' default payments in Taiwan.

Here you can find my article about [SupportVectorMachine](https://medium.com/@abdullah.hosam13/a-comprehensive-guide-to-support-vector-machines-svms-e8d5584434eb) which I used in this project. 

**About the project**

**What is Credit card default** it refers to the failure of a cardholder to make the required minimum payment on their credit card account within the specified time frame. When a cardholder defaults on their credit card, it typically means that they have fallen significantly behind on their payments and have breached the terms and conditions agreed upon with the credit card issuer.

Defaulting on a credit card can have various consequences, including:

* Late Payment Fees: Credit card issuers often charge late payment fees when cardholders fail to make their minimum payment on time. These fees can add to the outstanding balance, increasing the overall debt.

* Increased Interest Rates: Defaulting on a credit card may result in the credit card issuer increasing the interest rate on the account. Higher interest rates can make it more difficult for the cardholder to repay the debt, as a larger portion of their payments goes towards interest charges.

* Negative Impact on Credit Score: A credit card default can significantly impact the cardholder's credit score. Late payments and defaults are reported to credit bureaus, and they can remain on the individual's credit report for several years. A lower credit score can make it harder to obtain credit in the future and may result in higher interest rates for other loans or credit cards.

* Collection Efforts: If a credit card default persists, the credit card issuer may employ collection efforts to recover the outstanding debt. This can involve contacting the cardholder via phone calls, letters, or engaging with a collection agency. In extreme cases, legal action may be taken, leading to a lawsuit or wage garnishment.

* Loss of Credit Card Privileges: After defaulting on a credit card, the issuer may suspend or cancel the cardholder's credit card privileges. This means the cardholder will no longer be able to use the card for purchases or cash advances.

**Support Vector Machine**
A Support Vector Machine (SVM) is a supervised machine learning algorithm used for classification and regression tasks. It is commonly used for solving binary classification problems, but it can also be extended to handle multi-class classification.

The basic idea behind SVM is to find an optimal hyperplane that separates the data points of different classes with the largest margin. In a binary classification scenario, the hyperplane is a decision boundary that separates the data points into two classes. The margin is the distance between the hyperplane and the nearest data points of each class, and SVM aims to maximize this margin.

**Advantages**:

* Effective in high-dimensional spaces: SVM performs well even when the number of features is greater than the number of samples, making it suitable for datasets with many features.

* Robust against overfitting: SVM aims to maximize the margin, which helps to prevent overfitting and generalizes well to unseen data.

*Versatile: SVM can handle both linearly separable and non-linearly separable data through the use of different kernels.

**Limitations**

* Computationally intensive: Training an SVM model can be computationally expensive, especially for large datasets.

* Sensitivity to feature scaling: SVM's performance can be affected by the scale of the input features, so it's important to scale them appropriately.

* Difficulty in handling large datasets: SVM's memory requirements increase with the size of the training dataset, which can be a challenge for very large datasets. 
