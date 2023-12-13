# MultiNERD-English-
NER model for MultiNERD (English) 
This repo contains .ipynb files  for finetuning Hugging Face NER(Named Entity Recognition) models on the [MultiNERD dataset](https://github.com/Babelscape/multinerd) for english. The base model used is [DistillBERT](https://huggingface.co/docs/transformers/model_doc/distilbert)

## Dataset
The MultiNERD dataset is available [here](https://huggingface.co/datasets/Babelscape/multinerd).
In the MultiNERD dataset there are 15 NER  categories :Person (PER), Location (LOC), Organization (ORG}), Animal (ANIM), Biological entity (BIO), Celestial Body (CEL), Disease (DIS), Event (EVE), Food (FOOD), Instrument (INST), Media (MEDIA), Plant (PLANT), Mythological entity (MYTH), Time (TIME) and Vehicle (VEHI);

## Usage of Files
The easiest way to use both the System A and System B files is run them directly on Google Colabatory. 
For inference, both models are uploaded to Hugging Face - [System A](https://huggingface.co/doomnova/distilbert_system_A) , [System B](https://huggingface.co/doomnova/distilbert_system_B)

For running the files on a local device with an environment, the necessary modules can be installed using - pip install -r requirements.txt

## Citations
