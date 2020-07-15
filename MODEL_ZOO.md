# Model Zoo

## Introduction

The models trained in our baseline are listed below. All models were trained 1 epochs under their respective backbones. Using the pretrained model provided by [Transformers](https://github.com/huggingface/transformers#model-architectures) and [LayoutLM](https://github.com/microsoft/unilm/tree/master/layoutlm#pre-trained-model).


## License

All models available for download through this document are licensed under the [Attribution-NonCommercial-NoDerivs License](https://creativecommons.org/licenses/by-nc-nd/4.0/).

## Models

The models trained on DocBank are available in the format used by Pytorch. 

|   |   name   |    backbone    |    url   |  size |
|---|:--------:|:--------------:|:--------:|:-----:|
| 0 |   BERT   | BERT-base      | [download](https://conversationhub.blob.core.windows.net/docbank/MODEL_ZOO/bert_base_50w_epoch_1.zip) | 387MB |
| 1 |   BERT   | BERT-large     | [download](https://conversationhub.blob.core.windows.net/docbank/MODEL_ZOO/bert_large_50w_epoch_1.zip) | 1.2GB |
| 2 |  RoBERTa | RoBERTa-base   | [download](https://conversationhub.blob.core.windows.net/docbank/MODEL_ZOO/roberta_base_50w_epoch_1.zip) | 441MB |
| 0 |  RoBERTa | RoBERTa-large  | [download](https://conversationhub.blob.core.windows.net/docbank/MODEL_ZOO/roberta_large_50w_epoch_1.zip) | 1.2GB |
| 1 | LayoutLM | LayoutLM-base  | [download](https://conversationhub.blob.core.windows.net/docbank/MODEL_ZOO/layoutlm_base_50w_epoch_1.zip) | 398MB |
| 2 | LayoutLM | LayoutLM-large | [download](https://conversationhub.blob.core.windows.net/docbank/MODEL_ZOO/layoutlm_large_50w_epoch_1.zip) | 1.2GB |