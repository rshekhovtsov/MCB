# MCB-10
* MCB.xlsx - всё вместе на 3 листах: группировка диагнозов, группы диагнозов и диагнозы 
* MCB-1.csv - отдельно группировка диагнозов
* MCB-2.csv - отдельно группы диагнозов
* MCB-3.csv - отдельно диагнозы 

Разделитель - ";", то есть читаем так:
```python
pd.read_csv('\data\mcb\mcb-3.csv', sep=';')
```
