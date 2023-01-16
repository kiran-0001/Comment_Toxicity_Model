# Comment Toxicity Model With Natural Language Processing and Tokenization
#### Inspired By Nicholas Renotte with optimizations and additions for my experimentation
## Research Background
> Comment toxicity is a major issue in online communication, as toxic comments can lead to a negative user experience and can contribute to the spread of hate speech. Deep learning models have been applied to the task of detecting toxicity in comments, using techniques such as natural language processing and machine learning.


## Workflow
> ***CSV ––> Inputs(strings) ––> Labels(mullti-binary classification) AND (Tokenization (text vectorization layer in Keras) ––> embedded vector) ––> Deep Neural Network(lstm layers for working with sequence of embeddings) ––> Serialize into H5 Format ––> Integrate Model to Gradio App*** 
***
# Conclusion
>
> This model is decent at classifying a given comment's toxicity, and it will only get better given more training time.
> 
> However, it would reason that a pre-trained transformer would be far superior.
>
> Note that to arrive at this conclusion the model was initially trained for roughly an hour.


***P.S Gradio is FANTASTIC. Can't help but wonder who makes these amazing tools...***

***

## **FULL DOCUMENTATION AND CONSTRUCTION IN MODEL FILE(.ipynb)**
