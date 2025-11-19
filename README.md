In this project I fine-tuned an open source LLM (LLAMA 3.1 8B) model on predicting prices of items using QLORA.
The training data was obtained from hugging face. 

There are three main jupyter notebooks:
1. data_prep.ipynb : In this notebook I preprocess the data so that it is ready to be used for fine-tuning.
2. fine_tune_llm: In this notebook I fine-tuned the model
3. eval.ipynb: In this notebook I compare the open-source model performance as compared to the fine-tuned one.

The fine-tuning was done on an L-40 cloud gpu and the inference was done on rtx-4070 mobile gpu. The fine-tuning only took
about an hour and from this fine-tuning I was able to improve accuracy from 81% to 90%. The cloud gpu costed about a dollar.
