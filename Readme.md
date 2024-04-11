# 电磁材料数据库（2024--04--11）

## 数据载体

- 由于数据库的建立需要大量的手工录入，因此考虑采用`Excel`，拓展名为`.xlsx`；
- 数据库名称为`eledata.xlsx`；
- 数据库有两个`sheet`，分别是记录介电常数的`eps`和记录磁导率的`mu`.



## 数据标签

- `eps`中数据标签含义

  - `name of material` 材料名称；

  - `min relative permittivity (Re)` 最小相对介电常数的实部；

  - `min relative permittivity (Im)` 最小相对介电常数的虚部，缺省为不存在；

  - `max relative permittivity (Re)` 最大相对介电常数的实部，缺省为不存在；

  - `max relative permittivity (Im)` 最大相对介电常数的虚部，缺省为不存在；

  - `min working frequency(f, Hz)` 测量时相应的最小工作频率，单位是赫兹(Hz)；

  - `max working frequency(f, Hz)` 测量时相应的最大工作频率，单位是赫兹(Hz)；

  - `reference material` 材料参数来源的参考资料.

  ------

  

- `mu`中数据标签含义

  - `name of material` 材料名称；

  - `min relative permeability (Re)` 最小相对磁导率的实部；

  - `min relative permeability (Im)` 最小相对磁导率的虚部，缺省为不存在；

  - `max relative permeability (Re)` 最大相对磁导率的实部，缺省为不存在；

  - `max relative permeability (Im)` 最大相对磁导率的虚部，缺省为不存在；

  - `min working frequency(f, Hz)` 测量时相应的最小工作频率，单位是赫兹(Hz)；

  - `max working frequency(f, Hz)` 测量时相应的最大工作频率，单位是赫兹(Hz)；

  - `reference material` 材料参数来源的参考资料.

    

## 说明

- 大多数材料给出的参数都是以图表形式给出，这里我们使用了软件https://getdata-graph-digitizer.software.informer.com/获得材料的具体参数；
- 对于相同名称材料，在不同频率下有不同材料参数，往往这种材料可以通过插值方法获得未知频率下的材料参数；



