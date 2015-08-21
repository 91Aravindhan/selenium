# selenium
                                JAVA TEST
TWO MARK
1.Instance variable is nothing but we declare any variable inside the classs.but outside the method,local variable can be declare inside the method.
EXAMPLE FOR INSTANCE
class Selenium
{
int x=25;
void show()
{
}
EXAMPLE FOR LOCAL VARIABLE
class Selenium
{
void show*()
{
int a=10;
}
2.
yes,main method can be overloaded,call the actual main method.
3.
We cannot change the value of the variable.
4.
we cannot create instanco of class
5.
Intefrace only extends using extension keyword...interface to class using implements keyword.
6.
we can use abstract keyword declare the abstract method
ex:abstract void selenium();
7.
It is types of access modifiers
private is use within the class.
public is use anywhere
proctected is use with in package.
8.
Method overloading is same method name different no of arguments.
Method overriding is same method name with same no of arguments in both parent and child class.
9.
Super keyword is used to refer to parent class object.
this keyword is used to current class object.

PART 2

I.error
2.30,40
3.error,final keyword is not in method.so error

PART 3

2.
interface X
{
void show();
}
interface Y
{
abstract void show();
}
class C implements A,B
{
public void show()
{
System.out.println("show");
}
public static void main(string[] args)
{
C obj=new C();
  obj.show();
  }
  }
  
3.

class Automation
{
void run()
{
System.out.println("running");
}
}
class Selenium extends Automation
{
void run()
{
System.out.println("running first");
}
public static void main(string[] args)
  Automation a=new Selenium();
  a.run();
  }}






