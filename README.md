# Kaggle Jigsaw Rate Severity of Toxic Comments 7th place solution (Naoism part)

* This is the repository of [colum2131](https://www.kaggle.com/columbia2131) part in the 7th place solution of [Jigsaw Rate Severity of Toxic Comments](https://www.kaggle.com/c/jigsaw-toxic-severity-rating/).
* The discription of this solution is available [here](https://www.kaggle.com/c/jigsaw-toxic-severity-rating/discussion/306366).
* The inference notebook in the competition is available [here](https://www.kaggle.com/columbia2131/jigsaw-team-ensemble-006-fix/notebook).

# Hardware

I used Kaggle Notebook.

# Data

* Jigsaw Rate Severity of Toxic Comments
	* Please download data to ./input from https://www.kaggle.com/c/jigsaw-toxic-severity-rating/data and unzip it.

# Model download

* I used 6 pretrained models that are publicly available in [Hugging Face](https://huggingface.co/).
	* roberta-base: https://huggingface.co/roberta-base
	* roberta-large: https://huggingface.co/roberta-large
	* unitary/toxic-bert https://huggingface.co/unitary/toxic-bert
	* microsoft/deberta-v3-base https://huggingface.co/microsoft/deberta-v3-base
	* unitary/unbiased-toxic-roberta https://huggingface.co/unitary/unbiased-toxic-roberta
	* unitary/multilingual-toxic-xlm-roberta https://huggingface.co/unitary/multilingual-toxic-xlm-roberta

# Train

* All model were trained on Kaggle Notebook. 