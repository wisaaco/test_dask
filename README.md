# test_dask



```python
import xarray as xr
from dask.distributed import Client, progress
c = Client("scheduler:8786")
c
```

### Auxiliar code for copypaste

ssh -L 8080:localhost:8888 isaac@cloudlab 

docker exec -it tests_jupyter_1 /bin/bash
