# Python实践总结

作者：ciaosulee
更新：05/06/2018

[TOC]

## Python底层函数不足

* list()无法按照表格中行元素顺序或列元素顺序来生成列表元素

```python
  list(DataFrame.iloc[1:5,:])
  list(DataFrame.iloc[:,1:5])
```

## Python语法糖
