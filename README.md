# Spam Detection using RNN

Detecting Spam with Deep Learning

## Project Overview

In this project, I explore the application of Recurrent Neural Networks (RNN) in spam detection. My model is trained on a dataset of labeled messages(5572 sample) and achieves a high accuracy in distinguishing between spam and legal messages.

## Key Features

* **Deep Learning**: Utilizes RNN to learn patterns and sequences in data
* **High Accuracy**: Achieves a high accuracy in spam detection(99.3% training accuracy and 95.52% testing accuracy)
* **Open-Source**: Fully open-source and available for modification and improvement

## Dataset

* **Description**: [Dataset has 2 columns Text and Labels(spam or not-spam)]
* **Source**: [https://archive.ics.uci.edu/dataset/228/sms+spam+collection]


## Data Preprocessing
* **Lowercasing**
* **Punctuation Removal**
* **Stop Words Removal**
* **Url Handled**
* **Whitespaces Removal**
* **Tokenization**
* **Lemmatization**

  
## Model Architecture

* **Embedding**: [Ivocab size=9011, max words=50 , 32]
* **RNN**: [SimpleRNN with 32 units]
* **Activation Functions**: [relu]
* **Optimizer**: [Adam]
* **Metrics**: [Accuracy]
* **Dropout Layer**: [After embedding(0.3) and after SimpleRNN(0.5)]

## Results

* **Accuracy**: [Training Accuracy:99.3% and Testing Accuracy:95.52%]
* **Loss**: [Training Loss:0.02 and Testing Loss:0.19]

## Usage

1. **Clone the repository**: `git clone https://github.com/Debopam-Pritam2014/Spam-Detection-Using-RNN.git`


## Contributing

Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.

## License

This project is licensed under the MIT License.
