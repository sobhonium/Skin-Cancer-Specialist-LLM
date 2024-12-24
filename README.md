# Skin-Cancer-Specialist-LLM
Fine tuning an LLM by the given dataset. The dataset represents the domain knowledge that the LLM should be an expert for.

The given notebooks are self-suffcient for fetching data (crawling), and fine-tuning an LLM (Llama, Mistral, Gemma, etc.) for training a domain knowledge.

## Step 1:
You can use ```Fetching-Data-from-PubMed.ipynb``` for fetching the dataset by the given keywords. Such notebook helps find PubMed papers undet that topic for fetching.

## Step 2:
After fetching the data, you need to put this into an instruct-input-output format in a json file to let it be trained via ```Fine-Tuning UnSloth on PubMed Articles.ipynb```.

## Step 3: 
You can insert prompts for getting outputs from the questions you ask.
