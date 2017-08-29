## Revisiting Unreasonable Effectiveness of Data in Deep Learning Era

[[arXiv](https://arxiv.org/abs/1707.02968)]

#### Description

Trained ResNet-101 on JFT-300M dataset. 

#### Key Points

* A lot more data -> better model
* Models with more capacity capitalize better on the increase in data

#### Commentary

Computationally, a dataset with 300 million images is infeasible. Even for Google, it took them 2 months to train 4 epochs using 50 K80 GPU's.

That being said, they did beat SoTa on multiple tasks by around 2-3% despite the model not being fine-tuned so we can likely expect better results (given infinite computation power)... which is comforting in some sense. 

#### Other

[Reddit Discussion](https://www.reddit.com/r/MachineLearning/comments/6o5ume/r_google_trains_network_on_300_million_images/) 
