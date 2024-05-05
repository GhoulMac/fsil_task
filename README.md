# fsil_task
Text analysis of all 10-k filings using  LDA and LLM to generate insights on the Filings

LDA and LLMs are both powerful tools for text analysis, but they come at text from different angles:

Latent Dirichlet Allocation (LDA): This is a statistical technique that identifies hidden thematic structures within a collection of documents. It treats documents as mixtures of various topics, and each topic is characterized by a probability distribution of words. LDA is like a detective uncovering underlying themes in a pile of text.

Large Language Models (LLMs): These are deep learning models trained on massive amounts of text data. They can perform a wide range of tasks,  like sentiment analysis, summarization, and even writing different kinds of creative content. LLMs are like super-readers who can analyze text, understand its nuances, and even generate similar content.

LDA: Effective in identifying latent topics in large datasets. Offers interpretable results with topic distributions.
LLMs: Highly versatile for various text analysis tasks. Can handle complex relationships within text and generate human-quality text.
Weaknesses

LDA: Relies on statistical assumptions and may not capture subtle semantic relationships. Requires pre-processing and choosing the right number of topics.
LLMs: Can be computationally expensive. Results might be opaque and lack interpretability. May struggle with factual accuracy and require fine-tuning for specific tasks.
Using them together:

While LDA and LLMs are distinct approaches, they can be complementary. Here are some ways to combine them:

Topic identification with LDA: Use LDA to identify topics in your text data.
LLM analysis on topics: Use an LLM to analyze the documents assigned to each topic by LDA. This can help you understand the specific language used within each theme.
Prompting LLMs with LDA topics: Use the topics identified by LDA to prompt an LLM for summaries or further analysis.
Overall, LDA and LLMs offer a powerful toolbox for text analysis. Understanding their strengths and weaknesses allows you to choose the right tool for the job, and in some cases, even leverage them together for deeper text insights.

Graphs like these can be obtained using the approach to determine in which year was the the text in the document was important and how much was it impacted by the current happenings araound the topic. We upload the 10-k filing doc, we clean the text file with beautifulsoup library and remove all the HTML tags and extract the text. After the text and the analysis is done using Google's Gemini API we generate insights and reports on the basis of our findings via LDA. 

![image](https://github.com/GhoulMac/fsil_task/assets/72375582/df7afb7c-b2dd-4b50-b5b7-b845ce15e348)

Deployment of the App is Left
