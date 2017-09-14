http://blog.csdn.net/lovelion/article/details/17517213

(一) 创建型

-,  简单工厂模式(3)
产品接口 Product
工厂类 Factory
Producer Factory.getProduct(String productType)

1,  工厂方法模式(5)
产品接口 Product
工厂接口 Factory createProduct()
具体的工厂类，重写createProduct方法，返回具体的Product实例
HelloProduct new HelloFactory().createProduct()

2,  抽象工厂模式(5)
产品接口 Product
工厂接口 Factory createProduct1() && createProduct2() && createProduct3()
具体的工厂类，重写所有的createProduct&()方法，返回一组具体的Product实例

3， 单例模式(4)
饿汉式 
懒汉式 双重检查锁以及violent
静态内部类
只有一个值的枚举类

4， 原型模式(3)
clone方法
深复制和浅复制

5， 建造者模式(2)
Actor ActorController(or Director).construct(Builder builder)
导演构建，传入具体的构建器，经过一系列的步骤，构建出具体的演员对象

（二） 结构型

6， 适配器模式(4)
Adapter 实现Target(需要被包装的类)接口，然后继承Adaptee(新的，用来适配的接口)类中的方法，并在其中做转化

7， 桥接模式(3)
把一个接口传进另外一个接口，然后就可以实现矩阵型的逻辑关联

8， 组合模式(4)
对待集合和个体，继承统一的接口，然后统一处理

9， 装饰模式(3)
Decorator同样继承Component接口，然后把之前的具体Component作为参数传入，然后返回Component接口对象使用

10，外观模式(5)
为客户端提供一组任务的一个简单的调用，隐藏具体复杂的内部实现细节

11，享元模式(1)


12，代理模式(4)
Proxy同样继承Subject接口，然后在里面实例化Subject的具体实例，然后想干嘛就干嘛

（三） 行为型

13，责任链模式(2)

14，命令模式(4)

15，解释器模式(1)

16，迭代器模式(5)

17，中介者模式(2)

18，备忘录模式(2)

19，观察者模式(5)

20，状态模式(3)

21，策略模式(4)

22，模板方法模式(3)

23，访问者模式(1)

3个不常用(1星) + 6个未完成