**Brand Measures**

The goal is to know about a product's popularity or to sell a product in a new segment based on the information available from telephonic survey data. After having sufficient information regarding that product we try to do marketing in various regions and increase the sales for revenue generation.

**STORYTELLING**

1. Understand the scenario
2. How Data Science can help
3. Data Science Requirements

For example, organization A sells multiple products X, Y, Z. The basic details required to know about the company are 
1. Sell the product 
2. Know the competition 
3. MRP 
4. Regions. 

Now, the company is launching a new product N. Marketing Team wants to know certain details to market the product. They are trying to launch the product especially in semi-urban and rural. they try to conduct a survey and get the data on Other choices they are now doing an online/offline form survey from which they get certain details like
1. Name, Phone, and details of the customer
2. Products they are using
3. offer sample product 

The survey is taken in four types of regions
1. A - Tier 1 cities ( direct marketing, TV, Radio)
2. B - Tier 2
3. C - Towns
4. D - Rural
The survey is taken from 10,000 people.

The sample product has been given to everyone who did the survey. Now, to follow up, a telephone call is done to know about the
1. How was it?
2. Improvements 
3. Pricey?
4. Other product similar
5. Dislike - other options

After the calls, we have the speech data. How to implement AI or Data Science? What can be done with this particular data? 
1. ASR - Automatic Speech Recognition ( Noisy, Quality of data/sound not good)

How to frame the problem statement?
    
How to identify the target (variable)?
Target: Keywords from conversational data

Identify the keywords (nouns, pronouns)
Building a grammatical engine helps to identify the keywords which will give an idea about the product 
Create a dictionary and store the necessary keywords in it.
The Dictionary consists of keywords like our own products, competitor's products, expensive, cheap, pricey, and availability.
    
Focus on the answers given by customers and not on the questions asked by the employee.

Tasks: (Possible steps)
1. Speech Separation
2. Diarization
3. Demasking

Now the Data has been separated.

**Module Exploration**

1. Audio Segmentation
2. Speaker Diarization
3. Speech Separation

After Data extraction, the data is present in speech/text format.
There might be errors so after passing through the speech engine, we use a spell corrector and find keywords. Then we will get the target. 

In summary,
1. Recording/conversation
2. ASR - Analyse the data
3. Separation technique
4. Spell corrector
5. Keyword spotting

**ASR**

1. DL approaches
2. API - Google, Azure, AWS
3. Offline API - CMU, Google, Wit.ai, Watson, Houndity

**Speech Recognition**

1. Speech Engine (PyPI) (Google Cloud API)

**API Based Approach**

Con - Response time (if its online)
Query --> Engine --> Response
Response Time 1, 2, 3 sec
Offline System Response time can be reduced by 1 or 2 sec
Google is the most famous cloud service 

**Deep Learning Approach**

ASR Engine:
1. Deep Speech (TF-based implementation) (from Google)
2. Fair Seq (from Facebook) (Pytorch-based implementation)
