# Chatbot 

An ask-me-anything chatbot using ChatGPT API that answers all your questions about data science, ML, and AI. Data used was scraped from subreddits


### Import Reddit data

We obtain our data by utlizing a Python Reddit API Wrapper library. The context contains top posts from 3 subreddits: Datascience, Machine Learning and Artificial Intelligence
[Documentation](https://github.com/bmar97/ChatBot/blob/main/subredditScraper.ipynb)

- **3** subreddits
- **2987** posts
- **230811** comments

## EDA
A look at the data shows a significantly more even distriubtion of post topics after 2019
![mypic](https://github.com/bmar97/ChatBot/blob/main/images/topic.EDA.png?raw=true)

### Wordcloud Visualizations 
Now lets take a look at the most common words and names found in posts/comments over the years

#### 2014
![mypic](https://github.com/bmar97/ChatBot/blob/main/images/wc.2014.png?raw=true)

#### 2017
![mypic](https://github.com/bmar97/ChatBot/blob/main/images/wc.2017.png?raw=true)

#### 2020
![mypic](https://github.com/bmar97/ChatBot/blob/main/images/wc.2020.png?raw=true)

#### 2023
![mypic](https://github.com/bmar97/ChatBot/blob/main/images/wc.2023.png?raw=true)


#### All-time
![mypic](https://github.com/bmar97/ChatBot/blob/main/images/wc.total.png?raw=true)

### Sentiment Analysis
To gain a better understanding of our data let's utilize a process of computationally identifying and categorizing opinions expressed in a piece of text, especially in order to determine whether the writer's attitude towards a particular topic is positive, negative, or neutral. Our topics are "chatgpt" and the data's associated emotions [Documentation](https://github.com/bmar97/ChatBot/blob/main/EDA.ipynb)

![mypic](https://github.com/bmar97/ChatBot/blob/main/images/sentiment.EDA.png?raw=true)

#### Emotion Recognition
Now we use a content - based classification problem involving concepts from the domains of Natural Language Processing as well as Machine Learning to determine the emotional sentiments of our data

![mypic](https://github.com/bmar97/ChatBot/blob/main/images/emotion.EDA.png?raw=true)

The data scraped from Reddit surprisingly maintains a strong sentimentality of neutral across all detected emotions. Understanding this we can assume the statistical bias, when a model or statistic is unrepresentative of the population, heavily leans towards neutrality and not towards positive or negative sentiments

## A chat with chatBot, 20 questions & answers informed by Reddit
##### Most intriguing questions are at the end [Documentation](https://github.com/bmar97/ChatBot/blob/main/redditChatBot.ipynb)

##### Q1
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.01%3A%20chatbot.png?raw=true)

##### Q2
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.02%3A%20data%20science%3F.png?raw=true)

##### Q3
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.03%3A%20skills.png?raw=true)

##### Q4
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.04%3A%20lan.speed.png?raw=true)

##### Q5
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.05%3A%20workforce.png?raw=true)

##### Q6
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.06%3A%20bias.png?raw=true)

##### Q7
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.07%3A%20wealth.distr.png?raw=true)

##### Q8
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.08%3A%20wealth.equity.png?raw=true)

##### Q9
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.09%3A%20ethics.png?raw=true)

##### Q10
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.10%3A%20humanity.png?raw=true)

##### Q11
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.11%3A%20intelligence.png?raw=true)

##### Q12
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.12%3A%20geopolitcal.png?raw=true)

##### Q13
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.13%3A%20warfare.png?raw=true)

##### Q14
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.14%3A%20adapt.png?raw=true)

##### Q15
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.15%3A%20soc.manipulation.png?raw=true)

##### Q16
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.16%3A%20privacy.png?raw=true)

##### Q17
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.17%3A%20industry.challenges.png?raw=true)

##### Q18
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.18%3A%20Ai.limitations.png?raw=true)

##### Q19
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.19%3A%20failure.png?raw=true)

##### Q20
![mypic](https://github.com/bmar97/ChatBot/blob/main/chatBot%20Q%26A/q.20%3A%20consequences.png?raw=true)
