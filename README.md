# Chatbot-for-customer-support
Quick issue resolution to simpler queries of customer is needed but without chatbot it will be not possible to resolve customers queries. One customer support person solve only one customers query. 
## Pre-requisites
**NLTK(Natural Language Toolkit)**

[Natural Language Processing with Python](http://www.nltk.org/book/) provides a practical introduction to programming for language processing.

For platform-specific instructions, read [here](https://www.nltk.org/install.html)

### Installation of NLTK
```
pip install nltk
```
### Installing required packages
After NLTK has been downloaded, install required packages
```
import nltk
from nltk.stem import WordNetLemmatizer
nltk.download('popular', quiet=True) # for downloading popular packages
nltk.download('punkt') 
nltk.download('wordnet') 
```
```
pip install tensorflow
```

```
pip install random
```
```
pip install tflearn
```
## How to run
```
venv\Scripts\activate
```
* Through Terminal
```
python chatbot_customer_support.py
```
![Alt text](https://github.com/dkokane0/Chatbot-for-customer-support/blob/main/output/file_tree.PNG)

![Alt text](https://github.com/dkokane0/Chatbot-for-customer-support/blob/main/output/venv_create.PNG)

![Alt text](https://github.com/dkokane0/Chatbot-for-customer-support/blob/main/output/output.PNG)

