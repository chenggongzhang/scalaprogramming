1. 在scala中，public是默认访问级别。也就是说，如果在类成员中不加访问修饰符，那就是public。
2. 方法或函数的内部不推荐使用return，这是因为scala鼓励程序员将方法或函数看做一个最终得到一个值的表达式，并且这些方法或函数应该是短小精悍的，而不是冗长繁复的。
3. 在scala中，对于返回值为Unit类型的方法，其目的在于体现其副作用，这些方法称为“过程”（procedure）。
4. scala取消了类的静态成员，代之以单例对象object。当一个单例对象和一个类同名时，该单例对象被称为该类的伴生对象。类和其伴生对象可以相互访问private成员。单例对象由于其“单例”特性，不能作为一个类型，但另一方面，单例对象由于可以继承超类或混入特质，因此又可以被赋值给一个超类类型的变量。



