This project originates from a competition that was hosted on Kaggle by Optiver.
The following are the relevant details for this competition: -
1) Competition name: -           Optiver-trading at close
2) Competition duration: -       Sep 20, 2023 - Dec 20, 2023
3) Competition URL: - 	         https://www.kaggle.com/competitions/optiver-trading-at-the-close
4) Additional knowledge: -       https://www.kaggle.com/code/tomforbes/optiver-trading-at-the-close-introduction
5) Presentation slides: -        Presentation - Introduction.pdf 
6) Project introduction video: - https://bit.ly/Optiver-Introduction

Models and performance metrics: -
1) LSTM model (Hidden size = 4, Input size = 9, Number of layers = 1, Number of parameters = 245)
   - Stock ID represented as 8-bit binary.
   - MAD achieved = 5.444
   - Jupyter notebook: - Optiver - Trading_at_the_Close.ipynb
   - Presentation slides: - Presentation - Model Dev Approach 1.pdf
   - Video presentation: - https://bit.ly/Optiver-Approach1

Other important project artefacts: -
1) Data Wrangler.ipynb: - This reads the 'train.csv' file as input and generates the 'train_wrangled.csv' file as output.
                          The purpose of this program is to carve out the data wrangling steps that are independent of the model being developed/trained 
                          and save the output in a separate file (train_wrangled.csv).
                          This file can then be consumed by programs created for development of various models. The time complexity associated with
                          data wrangling can thus be eliminated.