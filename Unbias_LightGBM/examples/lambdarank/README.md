# Modeling done with original LightGBM v 2.1.1

* Executed standard input with parameter configuration as in the unbiased setting.
* Results show nosignificant differences.


--- 

LambdaRank Example
==================

Here is an example for LightGBM to run lambdarank task.

***You should copy executable file to this folder first.***

Training
--------

For Windows, by running following command in this folder:

```
lightgbm.exe config=train.conf
```

For Linux, by running following command in this folder:

```
./lightgbm config=train.conf
```

Prediction
----------

You should finish training first.

For Windows, by running following command in this folder:

```
lightgbm.exe config=predict.conf
```

For Linux, by running following command in this folder:

```
./lightgbm config=predict.conf
```
