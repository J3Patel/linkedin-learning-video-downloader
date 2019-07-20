# LinkedIn Learning Downloader

#### Based on [mclmza's linkedin-learning-downloader](https://github.com/mclmza/linkedin-learning-downloader) Edited by Jatin Patel

Asynchronous scraping tool to fetch LinkedIn-learning's courses videos.

Dependencies:
- Python 3.6
- aiohttp
- lxml

#### Info

Please use this script for your own purposes.

This script was written for educational usage only.

Make sure your LinkedIn account is **NOT** protected with 2FA

#### Usage

> pip install -r requirements.txt

Edit config.py file (username, password and courses slugs)  

```Course's slug can be obtained using its url
e.g:
COURSE URL: https://www.linkedin.com/learning/learning-autodesk-inventor/creating-a-base-extrusion
->
SLUG: learning-autodesk-inventor
```

> python3 linkedin_learning.py


############################################################################################
