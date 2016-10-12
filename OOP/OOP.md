###面向对象编程
Object-oriented programming (OOP) is a programming paradigm based on the concept of "objects", which may contain data, in the form of fields, often known as attributes; and code, in the form of procedures, often known as methods.

译文：面向对象编程是一套基于‘对象’这个概念的编程方法论。
一个对象中会包含数据，通常叫‘属性’，也会包含一些函数。通常叫做方法。
eq:
var Pan = new Person('Pan');---对象
class Person{               ---
      constuctor(name){     ---类
        this.name = name
      }
  }
类---实例化--->对象
####class和object
object：对象，class：类。
对象是类的实例化，例如人是一个类，人有名字这个属性，但没有具体值。把人这个类实例化一个具体的人，给这个人具体赋值，这个具体的人，就是一个对象，对象种就有了实际的数据值了。
#####--因为面向对象编程对数据和方法进行了封装，造成类具有极强的可复用性，所以在大型项目中面向对象几乎是标配了。全栈JS开发者，用react写前端，用nodejs写后台，都是离不开对象的。任何编程都要考虑两个要素：数据和方法。面向对象先考虑的是数据，后考虑方法，而面向过程编程正好相反。
