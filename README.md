# LogReg-Bitmex

Wrote a supervised LogReg model for position reccomendation on XBTUSD perpetual futures on Bitmex
This model produces very littly alpha, but was more an experiment on learning about the process and potential applications of ML as a form of quantative analysis

This project consists of four jupyter notebooks

pulldata.ipynb - interaces with Bitmex API through websocket and REST technology in order to pull realtime data
db_update.ipynb - neatly stores pulled data into mongoDB database in 5m timespace
customipynb - contains my custom implementations for some pytorch functions. These include the LogReg ANN, custom dataloader, and custom                 normalize function
train.ipynb - training and eval functions for model
