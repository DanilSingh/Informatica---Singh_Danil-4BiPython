# Un notebook riproducibile e pulito prima del commit

```python
variabile = 3
```

```python
print(variabile)
```

Il Kernel continua a stamapare la variabile anche se la cella prima viene eliminata 
perchè il se facciamo riaprtire la cella il kernel comunque ricorda la variabile creata finchè non viene riavviato

ERRORE:
```python
NameError                                 Traceback (most recent call last)
Cell In[2], line 1
----> 1 print(variabile)

NameError: name 'variabile' is not defined
```

3. Ho rimesso la variabile prima del codice e facendo il Run All

