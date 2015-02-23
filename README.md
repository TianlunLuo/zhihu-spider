# zhihu-spider
A web spider for zhihu.com, which is used for [ZhihuHot](http://zhihuhot.sinaapp.com/).  
This spider can scrape question & topic data from zhihu.com.

# Author
I'm Morgan Zhang, a graduate computer science student in University of San Francisco.  
I'm looking for a software engineer internship in summer 2015.

### Why I made it
Coding for fun as well as learn Python.

### Contact Information
MorganZhang100@gmail.com

# Use it

## What do you need to run it
- Python 2.7.6 (Maybe it work for other versions.) 
- MySQL
- BeautifulSoup

## How to use it
1. Download the code
1. Run init.sql to set up datebase.
1. Find out your cookie of zhihu.com throught browser's developer tool.
1. Modify config.ini
1. Use ```python question.py``` to scrpy questions from zhihu.com
1. Use ```python topic.py``` to scrpy topics from zhihu.com

# Warning
You can change thread amount in config.ini to make this spider run faster.  
But your IP may be blocked from zhihu.com if you connect to zhihu.com too frequently.  
You'd better use proxy when you use multi thread mode.

# License
The MIT license.
