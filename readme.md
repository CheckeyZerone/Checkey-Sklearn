# 使用说明

GitHub: [https://github.com/CheckeyZerone/Checkey-Sklearn](https://github.com/CheckeyZerone/Checkey-Sklearn)
PyPI: [https://pypi.org/project/checkey-sklearn/](https://pypi.org/project/checkey-sklearn/)

## 版权声明
    Checkey-Sklearn
    Copyright (C) 2023  CheckeyZerone

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU Affero General Public License as published
    by the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU Affero General Public License for more details.

    You should have received a copy of the GNU Affero General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.

## 安装方法
```commandline
pip install csklearn
```

## 依赖的第三方模块包

```
numpy
pandas
scikit-learn
```

## 实现算法

- 朴素贝叶斯改进
- 熵权-TOPSIS模型

## 使用方法

```python
model = Model(*params)
model.fit(x_train[, y_train, params])
model.predict(x_test)  # or model.transform(x_test)
```
