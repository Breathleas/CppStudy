dynamic_cast 是一个运算符，执行从基类向派生类的带检查的强制类型转换。当基类中至少含有一个虚函数时，该运算符负责检查指针或引用所绑定的对象的动态类型。如果对象类型与目标类型(或其派生类)一致，则类型转换完成。否则，指针转换将返回一个值为0的指针；引用转换将抛出一个异常。