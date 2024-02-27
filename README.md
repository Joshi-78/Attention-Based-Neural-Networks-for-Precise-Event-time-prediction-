#  Attention Based Neural Networks for Precise Event Time Prediction

Contemporary data acquisition methods consistently yield voluminous event sequence data across numerous domains,such as social media, healthcare, and financial markets. These data often exhibit complex short- and long-term temporal dependencies. However, most existing recurrent neural network-based point process models fail to capture these dependencies, resulting in unreliable prediction performance.
To address this issue, we propose the TransTPP model, which leverages the self-attention mechanism to capture long-term dependencies while maintaining computational efficiency. Numerical experiments on various datasets demonstrate that the TransTPP model outperforms existing models in terms of both likelihood and event prediction accuracy by a significant margin. Furthermore, the TransTPP model is quite general and can be extended to incorporate additional structural knowledge. We provide a concrete example where the TransTPP model achieves improved prediction performance for learning multiple point processes when incorporating their relational information.
## Project Overview
Data Collection:
MIMIC,Retweet Data sets were used
The model is designed for event sequence data, so the data collection process likely involves gathering sequences of events from various sources depending on the specific application 

Data Cleaning:

Event sequence data can contain inconsistencies and errors. Cleaning might involve:
Identifying and removing missing or irrelevant entries

Data Collection:

The model is designed for event sequence data, so the data collection process likely involves gathering sequences of events from various sources depending on the specific application (e.g., social media platform APIs, patient records databases).

Data Splitting:

The data is typically split into three sets:
Training set: Used to train the model.
Validation set: Used to monitor the model's performance during training and prevent overfitting.
Model Architecture: This is based on Transformer Architecture on Time Event Sequences.
Model Training: The model is trained using the Adam optimizer and NNLL loss function.
Model Evaluation: The trained model's accuracy is evaluated on the test data.
## Requirements
To run this project, you will need the following libraries:

1.PyTorch
2.sklearn
3.numpy
4.matplotlib
5.pandas

## Usage
Clone the repository.
Install the required libraries mentioned above.
Run the Main.py to train the Transformer model.

## Contribution
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please feel free to create a pull request.
