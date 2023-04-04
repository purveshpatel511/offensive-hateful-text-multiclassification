# Offensive and Hateful Text Multiclassification

This is pre-trained roBERTa model to identify the hateful and offensive speech. Model is trained on the original dataset and has the accuracy of 94.5% on the test datasets. Model can classify the given input text into three different categories which are hateful, offensive and neither of them.

## Requirements

Before you run this projects, you should install the `requirements.txt` file so you don't get any package error in future.

Install all the required package by running following command:

`pip install -r requirements.txt`

Packages used by the model are:

- transformers
- datasets
- scikit-learn
- wandb

## Train the Model

To train the model by yourself, go over to the file `text-multiclassification.ipynb`. This file is use to train the model from the scratch.

Feel free to try this notebook and train a model by yourself. The comments in file will guide you through your journey.

## Run/Use the Model

If you want to direct run or use the model then head over to the `application.py` file. This file has the nice interface to interact with the model and display it nicely.

## Dataset

You can find the dataset that is used to train the model, on this [page](https://huggingface.co/datasets/badmatr11x/hate-offensive-speech/).

The dataset split into three parts train, validation and test.

## Model

You can directly use this pre-trained model for your own use or personal project from this [page](https://huggingface.co/badmatr11x/distilroberta-base-offensive-hateful-speech-text-multiclassification/).

## Space

This model is currently live on the Internet. To interact with model and play with model, head over to this [space](https://huggingface.co/spaces/badmatr11x/offensive-hateful-speech-multiclassification) and enjoy! =)

## Contributing

Contributions are always welcome!

Open a Pull Request for any appropriate model changes and feature updates.

## Authors

- [@purveshpatel511](https://www.github.com/purveshpatel511)
