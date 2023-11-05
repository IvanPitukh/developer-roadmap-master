# How are LLMs Built?

On a high level, training an LLM model involves thre steps i.e. data collection, training and evaluation. 

- **Data Collection** The first step is to collect the data that will be used to train the model. The data can be collected from various sources such as Wikipedia, news articles, books, websites etc.

- **Training**: The data then goes through a training pipeline where it is cleaned and preprocessed before being fed into the model for training. The training process usually takes a long time and requires a lot of computational power.

- **Evaluation**: The final step is to evaluate the performance of the model to see how well it performs on various tasks such as question answering, summarization, translation etc.

The output from the training Pipeline is an LLM model which is simply the parameters or weights which capture the knowledge learned during the training process. These parameters or weights are typically serialized and stored in a file, which can then be loaded into any application that requires language processing capabilities e.g. text generation, question answering, language processing etc.