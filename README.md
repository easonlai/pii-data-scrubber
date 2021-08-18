# PII Data Scrubber 

Version 1.2 - Added Price information (by $ amount, including in sentence) scrubbing.
Version 1.1 - Added Hong Kong Identity Card (HKID) number (including in sentence) scrubbing.

This is demo repo to demonstrate how to leverage [Azure Text Analytics](https://docs.microsoft.com/en-us/azure/cognitive-services/text-analytics/overview) to perform [Personally identifiable information (PII)](https://en.wikipedia.org/wiki/Personal_data) data scrubbing by Python (Jupyter Notebook). This is important part of [data wrangling](https://en.wikipedia.org/wiki/Data_wrangling)/[data cleaning](https://en.wikipedia.org/wiki/Data_cleansing).

Sample PII data (data/pii-sample-data.csv) is contain dummy variations of Visa Card number, Master Card number, American Express Card number, Phone number, Name, Address, Email Address, Hong Kong Identity Card (HKID) number (including in sentence) & Price information (by $ amount, including in sentence).

![alt text](https://github.com/easonlai/pii-data-scrubber/blob/main/git-images/git-image-1.png)