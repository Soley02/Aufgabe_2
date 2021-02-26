# Aufgabe 2

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Soley02/Aufgabe_2/HEAD)

Ein Binder-Kompatibles Repository mit einer `requirements.txt` und `runtime.txt` Datei.

Sie können auch unter der folgenden Binder-URL dieses Notebook erzeugen:

https://mybinder.org/v2/gh/Soley02/Aufgabe_2/HEAD

## Ausführung:

Für die Auführung durch MyBinder, wurden die hier enthalten Dateien verwendet.

Die Daten welches in den ML-Beispielen verwendet wurden, sind ebenfalls direkt abrufbar im Code und müssen nicht zusätzlich heruntergeladen werden.

1. Schritt: Auf Badge von MyBinder klicken oder per LINK
2. Schritt: Warten bis alle erforderlichen Pakete/Module durch MyBinder hinzugefügt sind
3. Schritt: MyBinder wurde erfolgreich durchgeführt und Jyupter Notebook (Nbviewer) öffnet sich
4. Schritt: Der Code Aufgabe_2.ipynb kann via MyBinder ausgeführt und Logfiles automatisch erstellt werden

Bei Interesse, kann ebenfalls der Code "2-Mnist Mit Multi-Layer Perceptron.ipynb" heruntergeladen werden und via Jyupter Notebook ausgeführt werden. Die erforderlichen Dateien zur Ausführung des Codes sind ebenfalls in diesem Repository vorhanden.  

### Notes

Die `requirements.txt` Datei listet alle Python-Bibliotheken auf, die für dieses Notebook erforderlich sind. Diese werden automatisch installiert:

```
pip install -r requirements.txt
```

In diesem Beispiel enthaltenen Bibliotheken sind:

- pandas = 1.0.1
- numpy = 1.18.1
- matplotlib = 3.1.3
- seaborn = 0.11.1
- scikit-learn = 0.24.1
- keras = 2.3.1
- tensorflow

# Ausgabe auf Console
```
Fit model on training data
Train on 50000 samples, validate on 10000 samples
Epoch 1/2
50000/50000 [==============================] - 7s 137us/sample - loss: 0.3466 - sparse_categorical_accuracy: 0.9029 - val_loss: 0.1751 - val_sparse_categorical_accuracy: 0.9509
Epoch 2/2
50000/50000 [==============================] - 7s 138us/sample - loss: 0.1577 - sparse_categorical_accuracy: 0.9537 - val_loss: 0.1309 - val_sparse_categorical_accuracy: 0.9626
```
Epoche 1: sparse_categorical_accuracy: 0.9029 - val_loss: 0.1751 - val_sparse_categorical_accuracy: 0.9509

Epoche 2: sparse_categorical_accuracy: 0.9537 - val_loss: 0.1309 - val_sparse_categorical_accuracy: 0.9626
____________________________________________________________________________________________________________________________________
```
50000/50000 [==============================] - 9s 173us/sample - loss: 0.3016 - sparse_categorical_accuracy: 0.9133
fit ran in: 8.655128717422485 sec
50000/50000 [==============================] - 9s 183us/sample - loss: 0.1425 - sparse_categorical_accuracy: 0.9574
fit ran in: 9.135992050170898 sec
<tensorflow.python.keras.callbacks.History object at 0x7fb001527090>
predict ran in: 0.28151822090148926 sec
predict ran in: 0.31096410751342773 sec
[[6.14702600e-09 7.50709805e-09 1.06676980e-05 ... 9.99921441e-01
  7.22658001e-07 6.13122756e-06]
 [1.41714040e-07 2.41886892e-06 9.99968886e-01 ... 6.32140282e-13
  1.12440762e-06 1.15843880e-11]
 [2.38624784e-06 9.98613358e-01 8.35081097e-04 ... 2.87782110e-04
  1.09913686e-04 1.39313106e-05]
 ...
 [5.56173857e-12 1.31396438e-09 2.08277201e-10 ... 1.79586863e-07
  4.72318152e-06 5.08616446e-04]
 [6.07364612e-08 5.26258255e-08 1.46197263e-10 ... 8.63720118e-08
  1.82177519e-05 2.50953391e-09]
 [8.20112177e-07 1.59678416e-11 8.68839081e-08 ... 1.89171359e-10
  2.79791723e-09 8.33080605e-10]]
```
sparse_categorical_accuracy: 0.9133 / fit ran in: 8.655128717422485 sec 

sparse_categorical_accuracy: 0.9574 / fit ran in: 9.135992050170898 sec

predict ran in: 0.28151822090148926 sec 

predict ran in: 0.31096410751342773 sec 

____________________________________________________________________________________________________________________________________

# Ausgabe auf LogFile
```
INFO:root:fit ran in: 6.9062581062316895 sec
INFO:root:<tensorflow.python.keras.callbacks.History object at 0x7fe9c81c2310>
INFO:root:fit ran in: 7.2004218101501465 sec
INFO:root:predict ran in: 0.7085063457489014 sec
INFO:root:[[3.9486068e-08 2.1983795e-09 7.6838014e-06 ... 9.9995577e-01
  6.4028228e-07 5.7066512e-07]
 [5.5616717e-10 1.9435910e-07 9.9999964e-01 ... 8.6448519e-13
  1.5083966e-10 8.3847161e-16]
 [3.9545075e-06 9.9305224e-01 1.6709617e-03 ... 3.4542033e-03
  1.0789203e-03 3.1086965e-05]
 ...
 [5.8697108e-10 4.5543451e-11 8.1743147e-11 ... 1.5621517e-05
  8.3484840e-05 8.1325264e-04]
 [1.7630679e-10 2.1816998e-10 3.8712237e-08 ... 6.2148825e-10
  9.5406140e-06 9.3240485e-12]
 [3.7211529e-09 1.1715197e-14 1.0348017e-06 ... 1.2872167e-15
  1.8111427e-09 5.1400609e-11]]
INFO:root:predict ran in: 0.7880904674530029 sec
```
fit ran in: 6.9062581062316895 sec 

fit ran in: 7.2004218101501465 sec 

predict ran in: 0.7085063457489014 sec 

predict ran in: 0.7880904674530029 sec 

# Unit Test

## Test OK
```
setUp
__init__ ran in: 3.814697265625e-06 sec
.
fit ran in: 15.610037088394165 sec
setUp
__init__ ran in: 2.86102294921875e-06 sec
.
fit ran in: 16.504836797714233 sec
Classification report for classifier:
              precision    recall  f1-score   support

        0.0       0.78      0.94      0.85       980
        1.0       0.76      0.96      0.85      1135
        2.0       0.79      0.64      0.71      1032
        3.0       0.67      0.76      0.71      1010
        4.0       0.71      0.77      0.74       982
        5.0       0.62      0.42      0.50       892
        6.0       0.69      0.84      0.76       958
        7.0       0.76      0.80      0.78      1028
        8.0       0.79      0.59      0.67       974
        9.0       0.78      0.58      0.66      1009

avg / total       0.74      0.74      0.73     10000


predict ran in: 0.06742596626281738 sec

----------------------------------------------------------------------
Ran 2 tests in 32.259s

OK
```

## Test Failed

```
setUp
__init__ ran in: 4.291534423828125e-06 sec
F
fit ran in: 19.956449031829834 sec
setUp
__init__ ran in: 2.86102294921875e-06 sec
F
fit ran in: 21.153944969177246 sec
Classification report for classifier:
              precision    recall  f1-score   support

        0.0       0.78      0.94      0.85       980
        1.0       0.76      0.96      0.85      1135
        2.0       0.79      0.64      0.71      1032
        3.0       0.67      0.76      0.71      1010
        4.0       0.71      0.77      0.74       982
        5.0       0.62      0.42      0.50       892
        6.0       0.69      0.84      0.76       958
        7.0       0.76      0.80      0.78      1028
        8.0       0.79      0.59      0.67       974
        9.0       0.78      0.58      0.66      1009

avg / total       0.74      0.74      0.73     10000

predict ran in: 0.18126606941223145 sec

======================================================================
FAIL: test_fit (__main__.TestInput)
----------------------------------------------------------------------
Traceback (most recent call last):
  File "<ipython-input-25-ca086a060c24>", line 40, in test_fit
    self.assertEqual(result, self.train_accuracy)
AssertionError: 72.442 != 73.4

======================================================================
FAIL: test_predict (__main__.TestInput)
----------------------------------------------------------------------
Traceback (most recent call last):
  File "<ipython-input-25-ca086a060c24>", line 49, in test_predict
    self.assertEqual(self.ta.predict(), self.test_accuracy)
AssertionError: 73.57000000000001 != 74

----------------------------------------------------------------------
Ran 2 tests in 41.315s

FAILED (failures=2)
```
