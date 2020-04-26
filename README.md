# Deep Learning: Detecting Fraudulent Healthcare Provider using AutoEncoder
# Introduction

In this article, I will share my experience that how to use the power of deep neural networks to effectively identify fraudulent healthcare providers from the health care transactions that can be identified as anomalies in a dataset. For this solution, I used autoencoder machine learning algorithm and implemented it in the H2O platform.

Let us start with the definition. An anomaly refers to a data instance that is significantly different from other instances in the dataset. Often these considered as statistical outliers or errors in the data before developing a predictive model. But sometimes an anomaly in the data may indicate some potentially harmful events that have occurred previously. In health care insurance claim data, those are fraudulent claims.


# Health Care Fraud

Healthcare provider fraud is one of the biggest problems facing Medicare. According to the government, the total Medicare spending increased exponentially due to fraud in Medicare claims. Healthcare fraud is an organized crime that involves peers of providers, physicians, beneficiaries acting together to make fraud claims. Insurance companies are the most vulnerable institutions impacted due to these bad practices. Due to this reason, insurance companies increased their insurance premiums, and as a result, healthcare is becoming costly matter day by day.

Just an example to show how big this problem is, According to HHS and DOJ, Health Care Fraud and Abuse Control Program Annual Report for Fiscal Year 2013, February 2014 (http://oig.hhs.gov/publications/docs/hcfac/FY2013-hcfac.pdf), Four hospital executives in Florida were convicted of paying bribes and kickbacks to obtain Medicare patients. The executives billed Medicare for treatments for which the patients were ineligible, falsified patient charts, and administered unnecessary psychotropic medications to make the patients appear to need intensive mental health services. Relationship scrutiny played an important part in this case; it revealed that providers were taking advantage of their patients by over-treating them and billing the government. 

Healthcare fraud and abuse take many forms. Some of the most common types of frauds by providers are:

·      Billing for services that were not provided.

·      Duplicate submission of a claim for the same service.

·      Misrepresenting the service provided.

·      Charging for a more complex or expensive service than was actually provided.

·      Billing for a covered service when the service actually provided was not covered.



# Anomaly Detection

Even though the fraudulent claims make a big impact on insurance companies, the fraud claims were only 2% of the whole claims. Since it is the low percentage of fraud. When analyzing normal claims these fraud claims often deviate from other normal claims as anomalies. These particular claims are different in that they do not match other expected patterns in the dataset. Such cases are commonly known as anomalies or rare events. This detecting these anomalies using machine learning algorithms helps to identify fraudulent providers.

There are many ML algorithms and packages available for this Anomaly detection; here the few...

·      K-Nearest Neighbors

·      Autoencoders - Deep neural network

·      K-means

·      Support Vector Machine

·      Naive Bayes

Since the fraud claims instance was low in number and makes in a highly imbalanced dataset, the unsupervised algorithm machine learning algorithm better for this problem. I used the new neural network architecture called Autoencoder.  Let us see how the autoencoder will work and I solved the fraud detection problem.

more detail visit [my blog](https://www.datasciencecentral.com/profiles/blogs/deep-learning-detecting-fraudulent-healthcare-provider-using)

