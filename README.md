📊 Typhoon Family Sentiment Analysis
🧠 Comparing GPT and VADER Models on Korean Drama Reviews
📝 Overview

This project presents a sentiment analysis of the newly released K-Drama Typhoon Family (태풍상사).
The main goal is to compare the accuracy, contextual understanding, and linguistic limitations between two sentiment analysis models — VADER and GPT — when analyzing Korean viewers’ reviews translated using DeepL.

📁 Dataset

Source: Viewer reviews collected from Naver reviews and community discussions until October 22nd, 2025. (Link: https://program.naver.com/p/36219184/contents)

Language: Korean (translated into English via DeepL).

Number of Reviews: 125

⚙️ Tools & Libraries

Python: Pandas, Numpy

VADER SentimentIntensityAnalyzer

OpenAI GPT 3.5 model

DeepL Translator API

Power BI for visualization

🔍 Methodology

Data Collection: Crawled viewer reviews using Selenium and exported them as CSV files.

Translation: Translated all Korean text to English using DeepL.

Sentiment Scoring:

VADER: Lexicon-based scoring of sentiment polarity.

GPT: Contextual classification of emotional tone.

Comparison: Analyzed discrepancies between two models.

Visualization: Illustrated sentiment distributions using Power BI dashboards.

📈 Results
Model	Positive	Neutral	Negative	Vague
GPT	93.6%	0.8%	4.8%	0.8% 
VADER	73.6%	19.2%	7.2% N/A

Both models indicate Typhoon Family received a highly positive reception from viewers.
However, the interpretation depth differed significantly between GPT and VADER.

⚖️ Model Comparison & Limitations
🔹 GPT (OpenAI)

Pro(s):

1. Convenient - Don't require English translation
2. Fast - Analyzed sentiments more than 100 within 1:30 minutes

Con(s):

1. Not free - Have to charge credits
2. Still analyzes with literal translation

🔹 DeepL Translation

Pro(s):

1. Free DeepL API

Cons:

1. Takes more steps than GPT
2. With the DeepL Python Package, some reviews were not translated

💡 Key Insights

Translation accuracy directly impacts sentiment outcomes.

GPT excels at nuanced interpretation, but cultural emotion markers still challenge even advanced models.

Combining both lexicon-based and contextual models yields a more balanced result.

🌐 Visualization Preview

<img width="1161" height="651" alt="Slide 1" src="https://github.com/user-attachments/assets/d780e926-7225-41ba-83b7-8124349edfdb" />
<img width="1160" height="647" alt="Slide 2" src="https://github.com/user-attachments/assets/2d907492-e4fa-42c8-b20a-b1b6846b4e5e" />
<img width="1160" height="646" alt="Slide 3" src="https://github.com/user-attachments/assets/95e9a33f-6116-4f7b-bc9a-4526fb94e286" />
<img width="1160" height="646" alt="Slide 4" src="https://github.com/user-attachments/assets/6ebffe01-ffa2-406a-899a-4ee9331e5da4" />
<img width="1160" height="647" alt="Slide 5" src="https://github.com/user-attachments/assets/ae8489bd-e930-44c6-b57f-846209c114c9" />
<img width="1158" height="647" alt="Slide 6" src="https://github.com/user-attachments/assets/84c5c331-c7c3-44f9-81c5-351b8cc693b5" />


Figure 1: Comparison of GPT and VADER sentiment classification results for Typhoon Family (2025).

🧩 Next Steps

Test with other Korean entertainment datasets to validate consistency.

Some people used machine learning for improved analysis of Korean reviews.

This will be updated once I have a better understanding of applying machine learning.

🔗 Connect with Me
If you’d like to discuss data analysis, Python, or Marvel shows 😄
Find me on LinkedIn[https://www.linkedin.com/in/jae-hwan-kim-274190100/] or contact me via email: jkim3615@gmail.com!
