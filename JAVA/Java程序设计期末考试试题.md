# Java程序设计期末考试试题、试卷、习题A卷


### 一、选择题。本题共20小题，每题2分，满分 40 分。
**1、在浏览器中执行applet 程序，以下选项中的哪个方法将被最先执行……… (    )**  

      A) init()    B) start()      C) destroy()        D) stop()

**2、有以下方法的定义，请选择该方法的返回类型（      ）**
```
      ReturnType  method(byte x, double y)
      {
              return  (short)x/y*2;
      }
```
      A）byte      B）short      C）int            D）double

**3、以下哪项可能包含菜单条（                ）。**

      A）Panel    B）Frame        C）Applet        D）Dialog

**4、Java application中的主类需包含main方法，main方法的返回类型是什么？（    ）**

      A）int        B）float      C）double        D）void

**5、Java application中的主类需包含main方法，以下哪项是main方法的正确形参？(  )**

      A） String  args    B）String  ar[]      C）Char  arg        D）StringBuffer args[]

**6、编译Java  Application 源程序文件将产生相应的字节码文件，这些字节码文件的扩展名为(      )。**

      A）.  java                      B)  .class
      C） . html                      D）  .exe

**7、设int型变量x = 1 , y = 2 , z = 3，则表达式  y＋＝z－－/x++  的值是(      )。**

      A）3                        B）3. 5
      C）4                        D）5

**8、不允许作为类及类成员的访问控制符的是(    )。**

      A）public                  B）private
      C）static                    D）protected

**9、 为AB类的一个无形式参数无返回值的方法method书写方法头，使得使用类名AB作为前缀就可以调用它，该方法头的形式为(      )。**

      A）static  void  method( )                    B）public  void  method( )    
      C）final  void  method( )                    D）abstract  void  method( )

**10、以下哪一个不是JAVA的标准数据流(    )。**

      A）标准输出数据流      B） 标准输入数据流    C）标准错误数据流    D） 标准运算数据流

**11．设有下面两个赋值语句： (  )**
```  java
        a = Integer.parseInt(“123”);
        b = Integer.valueOf(“123”).intValue();
```
**下述说法正确的是（    ）。**

      A）、a是整数类型变量，b是整数类对象。B）、a是整数类对象，b是整数类型变量。
      C）、a和b都是整数类对象并且值相等。  D）、a和b都是整数类型变量并且值相等。

**12、下列代表十六进制整数的是(  )**

      A）0123        B）1900        C）fa00        D）0xa2

**13、在Java中，实现用户界面功能的包是 …………………………… ………… (  )**

      A）java.applet                B）java.transaction        
      C）java.util                D）java.awt

**14、"++"运算符的操作数个数是( )**

      A）1个        B）2个        C）3个        D）4个

**15、已知：int[] a = new int[100];在下列给出的数组元素中，非法的是(  )**

      A）a[0]        B）a[1]        C）a[99]        D）a[100]

**16、用于输入压缩文件格式的ZipOutputStream 类所属包是(  )**

      A）、java.util.zip        B）、java.io        C）、java.nio        D）、java.util
**17、Window和Frame的默认布局管理器是(  )**

      A）、CardLayout        B）、FlowLayout        C）、BorderLayout        D）、GridLayout        

**18、在Java中，负责对字节代码解释执行的是______。 **

      A）垃圾回收器    B）虚拟机          C）编译器          D）多线程机制
**19、下列叙述中，正确的是 **

      A）Java语言的标识符是区分大小写的    B）源文件名与public类名可以不相同 
      C）源文件扩展名为.jar                  D）源文件中public类的数目不限

**20、在Java中，表示换行符的转义字符是 **

      A）\n            B）\f                C）'n'              D）\dd

### 二、填空题。本题共 13 小题，每空  1 分，满分 20 分。

**1抽象类是一种特殊的类，它本身不能够被_____,但可被继承.**

**2、开发与运行Java程序需要经过的三个主要步骤为_______、_________和______________。**

**3、设 x = 2 ，则表达式 ( x + + )／3 的值是__________。**

**4、在Java程序中，通过类的定义只能实现________重继承，但通过接口的定义可以实现________重继承关系。**

**5、执行以下几个语句后的输出结果是_______________。**
```
String  s = “This one” , s1=”This two”; 
int i=5
if (i>10)  
System.out.print(s) ; 
else
System.out.print(s1) ;
```

**6、程序中，若**
```
int x=667;
int& p=x;
```
**则 p= _____,**

**7、________是面向对象的语言一个重要的机制，通过这种机制可以在一个一般类的基础上建立新类。**

**8、如果类Alpha继承了类Beta，则类Alpha称为____类，类Beta称为___ 类。**

**9、已知int a,b; 则表达式a=2,b=5,a++;b++;a+b;的值为_________。**

**10、Applet生命周期方法有init( )，_______( )，stop( )和destroy( )。**

**11、Java技术的三大特征分别是__________  、 ___________、__________  。**

**12、面向对象的三个主要特征是__________  、 ___________、__________。**

**13、创建一个名为 MyPackage 的包的语句是____________________。**

### 三、问答题。本题共  5 小题，满分  26  分。

**1、什么叫方法的重载？构造函数可以重载吗？（4分）**
<br><br><br><br><br><br><br>
**2、Frame类对象的默认布局是什么？和Panel类对象的默认布局相同吗？（4分）**
<br><br><br><br><br><br><br>
**3、什么是异常？为什么要进行异常处理？        （4分）**
<br><br><br><br><br><br><br>
**4、谈谈final, finally, finalize的区别？（7分）**
<br><br><br><br><br><br><br>
**5、Overload和Override的区别。(7分)**
<br><br><br><br><br><br><br>


###四、设计题。本题共  2 小题，满分 14 分

**1. 请写一个程序, 类名叫HelloWorld，类里面有一个成员方法sayHello()，这个方法能向控制台输出HelloWorld.  (7分)**
<br><br><br><br><br><br><br>
**2. 用Java写一个Singleton出。Singleton模式主要作用是保证在Java应用程序中，一个类Class只有一个实例存在。(7分)**
<br><br><br><br><br><br><br>

# 答案

### 一、    选择题。本题共20小题，每题2分，满分 40 分。

| 题号 | 1 | 2 |  3  |  4 |   5  |  6   | 7  |  8  |  9    |10|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| 答案 | A | B | B | D | B | B | D | C | A | D |
| 题号 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 |
| 答案 | D | D | D | A | D | A | C | B | A | A |


### 二、填空题。本题共 13 小题，每空1 分，满分 20 分。
1、实例化
2、编辑源程序、编译生成字节码、解释运行字节码
3、0
4、单
5、This two
6、667
7、继承  
8、子，父
9、9
10、start
11、虚拟机、垃圾回收器、代码安全
12、封装、继承、多态
13、package  MyPackage ;  

### 三、问答题。本题共  5 小题，满分  26  分。      
1. (4分)、
答：一个类中可以有多个方法具有相同的名字，但这些方法的参数必须不同，
即或者是参数的个数不同，或者是参数的类型不同。
    构造方法可能重载。
2. (4分)
答：Frame容器的默认布局是BorderLayout布局，Panel容器的默认布局是
FlowLayout布局。所以是不同的。
3. (4分)
答：异常，是指由于程序运行时发生错误，从而导致程序错误结束。
在进行程序设计时，错误的产生是不可避免的，没有异常处理代码的程序，在运行时发生错误则可能非正常结束，引起严重问题。因此，Java给程序员提供了处理运行时错误的功能，称为异常处理。

4.  (7分)
答：final—修饰符（关键字）如果一个类被声明为final，意味着它不能再派生出新的子类，不能作为父类被继承。因此一个类不能既被声明为 abstract的，又被声明为final的。将变量或方法声明为final，可以保证它们在使用中不被改变。被声明为final的变量必须在声明时给定初值，而在以后的引用中只能读取，不可修改。被声明为final的方法也同样只能使用，不能重写
finally—异常处理时提供 finally 块来执行任何清除操作。如果抛出一个异常，那么相匹配的 catch 子句就会执行，然后控制就会进入 finally 块（如果有的话）
finalize—Java 技术允许使用 finalize() 方法在垃圾收集器将对象从内存中清除出去之前做必要的清理工作。这个方法是由垃圾收集器在确定这个对象没有被引用时对这个对象调用的。它是在 Object 类中定义的，因此所有的类都继承了它。子类覆盖 finalize() 方法以整理系统资源或者执行其他清理工作。finalize() 方法是在垃圾收集器删除对象之前对这个对象调用的

5. (7分)
答：方法的重写Overriding和重载Overloading是Java多态性的不同表现。重写Overriding是父类与子类之间多态性的一种表现，重载Overloading是一个类中多态性的一种表现。如果在子类中定义某方法与其父类有相同的名称和参数，我们说该方法被重写 (Overriding)。子类的对象使用这个方法时，将调用子类中的定义，对它而言，父类中的定义如同被"屏蔽"了。如果在一个类中定义了多个同名的方法，它们或有不同的参数个数或有不同的参数类型，则称为方法的重载(Overloading)。

### 四、设计题。本题共  2 小题，满分 14 分
1. (7分)
```
public class HelloWorld
{
     public void sayHello()
     {
            System.out.println(“HelloWorld!”)

    }
     public static void main(String args[])
     {
            HelloWorld hello=new HelloWorld();
            hello. sayHello
}
}
```

2. （7分）
```
public class Singleton { 
private Singleton ();
　　private static Singleton instance = null;
　　public static Singleton getInstance() {
　　    if (instance==null)
　　  instance＝new Singleton();
          return instance; 　
　　} 
}
```
