# Installation

This course assumes that you have a working installation Python 3.8+. 

1. Install/upgrade MIKE IO (`pip install --upgrade mikeio`)
2. (On PCs without MIKE Zero) Install [VC redist](https://aka.ms/vs/16/release/vc_redist.x64.exe)
3. Install matplotlib (`pip install matplotlib`)
4. Install netCDF4 (`pip install netCDF4`)
5. Install/upgrade ModelSkill (`pip install --upgrade fmskill`)

You will need to code in either VS Code or Jupyter Lab in this course.

## Test your installation

1. Open command prompt (`cmd.exe`)
2. Start python (`> ipython`) 
3. Run the following lines of code:

```
import sys
import numpy as np
import pandas as pd
import matplotlib as mpl
import mikeio
import fmskill
print(f"Python version: {sys.version}")
print("NumPy: " + np.__version__)
print("Pandas: " + pd.__version__)
print("Matplotlib: " + mpl.__version__)
print("MIKE IO: " + mikeio.__version__)
print("FMSkill: " + fmskill.__version__)
```

Can you say yes to the following questions? 

* My Python version is 3.8 or greater
* My NumPy version is 1.18 or greater
* My pandas version is 1.0 or greater
* My matplotlib version is 3.2 or greater
* My MIKE IO version is 1.0 or greater
* My ModelSkill version is 0.4 or greater
