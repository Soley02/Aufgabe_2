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

# Ausgabe
```
Fit model on training data
Train on 50000 samples, validate on 10000 samples
Epoch 1/2
50000/50000 [==============================] - 7s 137us/sample - loss: 0.3466 - sparse_categorical_accuracy: 0.9029 - val_loss: 0.1751 - val_sparse_categorical_accuracy: 0.9509
Epoch 2/2
50000/50000 [==============================] - 7s 138us/sample - loss: 0.1577 - sparse_categorical_accuracy: 0.9537 - val_loss: 0.1309 - val_sparse_categorical_accuracy: 0.9626
```
______________________
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
