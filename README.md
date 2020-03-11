# 气象应用开发基本程序库
提供一些关于气象科学计算的基础功能函数，包括数组处理、数学函数、物理常数、时间处理、客观分析等模块;  
以及气象诊断分析程序，包括动力, 热力, 水汽和天气特征分析等。

Only Python 3 is supported.

## Dependencies
Other required packages:

- Numpy
- Scipy
- Pyproj
- Python-dateutil
- Pandas
- Xarray
- Numba
- metpy

## Install
Using the fellowing command to install packages:
```
  pip install git+git://github.com/nmcdev/nmc_met_base.git
```

or download the package and install:
```
  git clone --recursive https://github.com/nmcdev/nmc_met_base.git
  cd nmc_met_base
  python setup.py install
```
