# python_environment_setuop
This file is an example to create a conda env with installed packages
<br>
The code to create env
<br>
`conda env create -f set_env.yml`
<br>
code to activate env
<br>
```conda to activate ats_env```

```python
from torch.utils.data.dataset import Dataset

class MyCustomDataset(Dataset):
    def __init__(self, ...):
        # stuff
        
    def __getitem__(self, index):
        # stuff
        return (img, label)

    def __len__(self):
        return count # of how many examples(images?) you have
```
