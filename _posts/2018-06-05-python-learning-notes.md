**Author：Ciaosu Lee**

**Update：05/06/2018**

### Python Code Weakness

* list()无法按照表格中行元素顺序或列元素顺序来生成列表元素

```python
  list(DataFrame.iloc[1:5,:])
  list(DataFrame.iloc[:,1:5])
```

### Python Grammer Sugar
