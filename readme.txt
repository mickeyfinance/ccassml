This problem is to explore building trading strategies using CCASS data. We collected public data of custodian distribution for each Hong Kong stocks listed on the main board and stored the data in AWS S3 bucket. We can use boto3 library to access the data. The sample data is also stored in dropbox for easier access. We then built some filters on stocks with the CCASS data and list out the trading days that meet certain requirements.

Then, we tried to design an automated trading solution for single stock using deep reinforcement learning.

Visit the Google Colab notebook:
https://colab.research.google.com/drive/1nKtlpk-_codwXkfFLdxOiNuBE_TE_tzg?usp=sharing