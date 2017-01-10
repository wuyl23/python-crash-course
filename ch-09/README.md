# 第9章 类

* 类名是首字母大写
* 以 `self`为前缀的变量都可供类中所有的方法使用
* 类中的每个属性都必须有初始值

**Python2.7**

	class ClassName(object):
		--snip---
		
### 继承

* 定义子类时，必须在括号内指定父类的名称
* `super().__init__()`
* 2.7: `super(ElectricCar, self).__init__()`


### 导入类

* 导入单个类: `from car import Car`
* 从一个模块导入多个类: `from car import Car, ElectricCar`
* 导入整个模块: `import car`
* 导入模块中的所有类: `from car import *`


### 标准库

* `collections`
