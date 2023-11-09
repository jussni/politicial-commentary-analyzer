# politicial-commentary-analyzer (BERT)
The project uses [FinBert](https://github.com/TurkuNLP/FinBERT/tree/master) for comparing given text to writings of four Finnish political commentators.

Model aims to predict which author wrote given article. [Simple Transformers](https://simpletransformers.ai/), [Google Colab](https://colab.google/) and [W&B](https://wandb.ai/site) are used for defining and training the model.

The model reaches 0.90 accuracy with out-of-sample test data.

Model can be used for predicting closest-matching author for a given text. [PCA](https://en.wikipedia.org/wiki/Principal_component_analysis) is employed to efficiently reduce the dimensions of the output.

An analysis and a scatter plot will be visualized as a final output. E.g:

> Text matches best with: Marko Junkkari
> 
> Raw output: [-2.96275067  0.11846653 -1.19843221  3.49551582]


![test-article](https://github.com/jussni/politicial-commentary-analyzer/assets/33765119/827c57e8-c275-4d4b-9b0a-a4dcea216c6f)




