## Nested Catalog Experiment

```
intake_server cat.yaml
```


```
import intake; cat = intake.open_catalog('intake://localhost:5000')
list(cat)
```