# Alexa CUMTD Bus Tracker
Alexa bus tracker for the CUMTD (Champaign/Urbana) bus system. Available to install on [this page](https://www.amazon.com/Daniel-Jamrozik-Champaign-Urbana-Times/dp/B06XDWHPT6/ref=sr_1_1?s=digital-skills&ie=UTF8&qid=1489084208&sr=1-1&keywords=cumtd).

The single .js file is meant to be ran as a lambda function on AWS. It also uses a DynamoDB key store to save default bus stops. The Lambda function will make API calls to CUMTD when triggered. A key for the CUMTD API will need to be obtained from the CUMTD website to query data.
