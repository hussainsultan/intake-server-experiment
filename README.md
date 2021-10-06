## Nested Catalog Experiment

```
intake-server cat.yaml
```


```
import intake; cat = intake.open_catalog('intake://localhost:5000')
list(cat)
```
