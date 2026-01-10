# EXPERIMENT3
## 3A.Title:Constructer Overloading
## SOURCE CODE:
``` java
class Student1 {
  String name;
  int age;
  double marks;
  Student1() {
  name="NotAssigned";
  age=0;
  marks=0.0;
 }
  Student1(String name,int age,double marks) {
  this.name=name;
  this.age=age;
  this.marks=marks;
 }
void display() {
System.out.println("Name:"+this.name);
System.out.println("Age:"+this.age);
System.out.println("Marks:"+this.marks);
}
}
class MainClass {
  public static void main(String[] args) {
     Student1 std1=new Student1();
     std1.display();
     Student1 std2=new Student1("hari",30,90);
     std2.display();
    }
}
```
# OUTPUT:
![output of 3a](3a.png)
