# PaddleOCR Multilingual Model Training Tutorial

PaddleOCR provides 80 language models, but still can not cover all. the released model can achieve a better result when you fine-tune with your own recognition data. If you have the following questions:

- Bad efforts when testing the original recognition model
- Lack of data and confusion about the training process
- Don't know how to replace or modify the dictionary

this tutorial will help you learn how to synthesize recognition images to train a custom recognition model, specifically, including:
- Corpus synthesis improves a certain category of recognition results, take Thai for example
- Use your own dictionary and corpus to train a model like the digital-only model, multilingual model, etc.
- A step-by-step training guide including how to configure training parameters via `.yml` configuration file
- Export the trained model to the inference model


<img src='https://user-images.githubusercontent.com/50011306/184822349-c214e8b7-90f5-4bab-9833-978b5055af04.png' width="600" heith="600">

Any question about the tutorial can be discussed in the [PaddleOCR's GitHub Discussion](https://github.com/PaddlePaddle/PaddleOCR/discussions)
