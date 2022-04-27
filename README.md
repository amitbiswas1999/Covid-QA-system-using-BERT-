
# Build and Deploy a COVID Q&A System using BERT

Develop a BERT Q&A system that provides real-time answers from over 200,000 COVID research papers

Steps:-
   
   1)Perform Exploratory data analysis and Topic modelling on the COVID dataset

   2)Create an indexed database of COVID research text in Elasticsearch

   3)Use haystack that retrieves and ranks candidate documents from Elasticsearch

   4)Develop the BERT Q&A Engine

   5)Building a simple UI with Streamlit
    
   6)Dockerize and deploy models


## Demo
![73adfae6e6069b978bff43e336891194b43daa01](https://user-images.githubusercontent.com/88819794/165460571-07460a0b-1721-4d6a-9afc-7bf1fc55bdd1.gif)

## Dataset

[Download Covid Dataset from here](https://ai2-semanticscholar-cord-19.s3-us-west-2.amazonaws.com/historical_releases/cord-19_2021-11-15.tar.gz
) 

## Tools
here I have used haystack which is an open-source framework for building search systems that work intelligently over large document collections.
Recent advances in NLP have enabled the application of question answering, retrieval and summarization to real world settings and Haystack is designed to be the bridge between research and industry.
For more explanation please refer [this docs](https://haystack.deepset.ai/overview/intro)
![image](https://user-images.githubusercontent.com/88819794/165554750-7be0322b-02b9-4ebf-94af-5231e5e78d31.png)


