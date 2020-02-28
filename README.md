# Sentiment-Analysis-RNN
## Introduction
Sentiment analysis is contextual mining of text which identifies and extracts subjective information in source material, and helping a business to understand the social sentiment of their brand, product or service while monitoring online conversations.
<br>
In this repository sentiment analysis model is build on LSTM cells. LSTM cells are used because it stores spatial information of past inputs as compared to other networks . 
## Base Info
Files and there uses are listed below
     
    Data -> Folder used for data storage
    Data Collection $prreprocessing -> Notebook for downloading data and preprocessing it.
    Model -> Contains code for RNN Model
    requirement -> txt file containg required lib
## Requirements

`Python : 3.X`

`Pip`

## Installation
Steps for installation
1. Download venv<br>
`pip install virtualenv`
2. Create virtual environment<br>
`pip venv env`
3. Activate virtual env<br>
`. env\bin\activate`
4. Install required library<br>
`pip install -r requirement.txt`  

## Architecture
> **First, we'll pass in words to an embedding layer**. We need an embedding layer because we have tens of thousands of words, so we'll need a more efficient representation for our input data than one-hot encoded vectors. 

> **After input words are passed to an embedding layer**, the new embeddings will be passed to LSTM cells. The LSTM cells will add recurrent connections to the network and give us the ability to include information about the sequence of words in the movie review data. 

> **Finally, the LSTM outputs will go to a sigmoid output layer**. We're using a sigmoid function because positive and negative = 1 and 0, respectively, and a sigmoid will output predicted, sentiment values between 0-1. 

        `Input(One Hot Encoded)  ->  Embedding Layer  ->  Lstm Cells   --> Output`

## Result
The testing accuracy and loss are,<br>

    Test Loss     :  .326
    Test Accuracy :  .871

## Contribution
For contribution 

1. Clone Repo<br>
`git clone https://github.com/soni-ratnesh/Sentiment-Analysis-RNN.git`
2. Install Dependencies <br>

3. Verify your changes

4. Submit Pull Request
