# Traffic Flow Prediction
Traffic Flow Prediction with Neural Networks(LSTM、GRU).

## Requirement
- Python 3.6    
- Tensorflow-gpu 1.5.0  
- Keras 2.1.3
- scikit-learn 0.19

## Train the model

**Run command below to train the model:**

```
python train.py --model model_name
```

You can choose "lstm", "gru"  as arguments. The ```.h5``` weight file was saved at model folder.




**Run command below to run the program:**

```
python main.py
```

These are the details for the traffic flow prediction experiment.


| Metrics | MAE | MSE | RMSE | MAPE |  R2  | Explained variance score |
| ------- |:---:| :--:| :--: | :--: | :--: | :----------------------: |
| LSTM | 7.21 | 98.05 | 9.90 | 16.56% | 0.9396 | 0.9419 |
| GRU | 7.20 | 99.32 | 9.97| 16.78% | 0.9389 | 0.9389|

![evaluate](/images/output.png)


