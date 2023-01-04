## SSD(the sum of squared differences)

 $cost = \sum(estiamte-actual)^2$

```Python
def ssd(estimate ,actual):
	return numpy.sum((estimate-actual)**2)
```

## SAD(the sum of absolute differences)

$cost = \sum \mid estimate-actual\mid$

```Python
def sad(estimate, actual):
	return numpy.sum(abs(estimate-actual))
```


