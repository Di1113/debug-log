4/20/2020
[python][conda][EE148-Caltech]
Error Msg: 
```
C:\Users\di111\Miniconda3\lib\site-packages\numpy\__init__.py:140: UserWarning: mkl-service package failed to import, therefore Intel(R) MKL initialization ensuring its correct out-of-the box operation under condition when Gnu OpenMP had already been loaded by Python process is not assured. Please install mkl-service package, see http://github.com/IntelPython/mkl-service
  from . import _distributor_init
Traceback (most recent call last):
  File "C:\Users\di111\Miniconda3\lib\site-packages\numpy\core\__init__.py", line 24, in <module>
    from . import multiarray
  File "C:\Users\di111\Miniconda3\lib\site-packages\numpy\core\multiarray.py", line 14, in <module>
    from . import overrides
  File "C:\Users\di111\Miniconda3\lib\site-packages\numpy\core\overrides.py", line 7, in <module>
    from numpy.core._multiarray_umath import (
ImportError: DLL load failed: The specified module could not be found.

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "C:\Users\di111\iCloudDrive\Documents\Caltech\EE148\HW1\caltech-ee148-spring2020-hw01\working_test.py", line 7, in <module>
    import numpy as np
  File "C:\Users\di111\Miniconda3\lib\site-packages\numpy\__init__.py", line 142, in <module>
    from . import core
  File "C:\Users\di111\Miniconda3\lib\site-packages\numpy\core\__init__.py", line 54, in <module>
    raise ImportError(msg)
ImportError: 

IMPORTANT: PLEASE READ THIS FOR ADVICE ON HOW TO SOLVE THIS ISSUE!

Importing the numpy c-extensions failed.
- Try uninstalling and reinstalling numpy.
- If you have already done that, then:
  1. Check that you expected to use Python3.7 from "C:\Users\di111\Miniconda3\python.exe",
     and that you have no directories in your PATH or PYTHONPATH that can
     interfere with the Python and numpy version "1.18.1" you're trying to use.
  2. If (1) looks fine, you can open a new issue at
     https://github.com/numpy/numpy/issues.  Please include details on:
     - how you installed Python
     - how you installed numpy
     - your operating system
     - whether or not you have multiple versions of Python installed
     - if you built from source, your compiler versions and ideally a build log

- If you're working with a numpy git repository, try `git clean -xdf`
  (removes all files not under version control) and rebuild numpy.

Note: this error has many possible causes, so please don't comment on
an existing issue about this - open a new one instead.

Original error was: DLL load failed: The specified module could not be found.

[Finished in 0.1s with exit code 1]
[cmd: ['C:/Users/di111/Miniconda3/python.exe', 'C:\\Users\\di111\\iCloudDrive\\Documents\\Caltech\\EE148\\HW1\\caltech-ee148-spring2020-hw01\\working_test.py']]
[dir: C:\Users\di111\iCloudDrive\Documents\Caltech\EE148\HW1\caltech-ee148-spring2020-hw01]
[path: C:\Program Files\Microsoft MPI\Bin\;C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.1\bin;C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.1\libnvvp;;C:\Windows\system32;C:\Windows;C:\Windows\System32\Wbem;C:\Windows\System32\WindowsPowerShell\v1.0\;C:\Windows\System32\OpenSSH\;C:\Program Files (x86)\Intel\Intel(R) Management Engine Components\DAL;C:\Program Files\Intel\Intel(R) Management Engine Components\DAL;C:\Program Files (x86)\NVIDIA Corporation\PhysX\Common;C:\Program Files\NVIDIA Corporation\NVIDIA NvDLISR;C:\Program Files (x86)\PharosSystems\Core;C:\Program Files\NVIDIA Corporation\NVIDIA NGX;C:\Go\bin;C:\Program Files\Git\cmd;C:\Program Files\NVIDIA Corporation\Nsight Compute 2019.1\;C:\Users\di111\AppData\Local\Programs\Python\Python38\Scripts\;C:\Users\di111\AppData\Local\Programs\Python\Python38\;C:\Users\di111\AppData\Local\Microsoft\WindowsApps;C:\Users\di111\AppData\Local\Programs\MiKTeX 2.9\miktex\bin\x64\;C:\Users\di111\go\bin;C:\Users\di111\AppData\Local\Packages\PythonSoftwareFoundation.Python.3.7_qbz5n2kfra8p0\LocalCache\local-packages\Python37\Scripts;]
```