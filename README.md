# adcases

basic construction for model training base on NSL_KDD dataset

## how to run
```python
python run.py <epochs nums> <runtype (0 for Gradient boosting, 1 for pytorch)> <model_name (with extension)>
```
default number of epochs is 50

## dataset details
[NSL_KDD](https://www.unb.ca/cic/datasets/nsl.html)
### new dataset
normal + ipsweet
### new dataset_1
normal + nmap + back
### new dataset_2
normal + multihop + loadmoudle + ftp_write + imap + phf
