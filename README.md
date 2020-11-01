# shiyan2
xueshengxuanke


## 实验目的
初步了解分析系统需求，从学生选课角度了解系统中的实体及其关系，学会定义类中的属性以及方法；
掌握面向对象的类设计方法（属性、方法）；
掌握类的继承用法，通过构造方法实例化对象；
学会使用super()，用于实例化子类；
掌握使用Object根类的toString（）方法,应用在相关对象的信息输出中。


## 实验方法
首先创建主类，然后在后面创建其他类，用作后续在主类中的输出。
根据需求，应有 people teacher student lesson 几个分类用作后续赋值。
完善分类中的内容，并在主类中用println输出。
运行程序，根据是否报错进行调试等。


## 实验过程
首先新建文件，并在其下创建五个class，分别为 shiyan2 people student teacher lesson。
将shiyan2作为主类。
根据需求，在people中创建变量name age number sex，并用this进行赋值
         在student中创建变量name age number，用super进行引用
         在teacher中创建变量name number sex，用suoer进行引用
         在lesson中创建变量name time number place，用this进行赋值
在主类中运用println进行其余类的信息输出
检查是否有误，运行
根据运行结果调试
运行成功


## 核心方法
'''
public class shiyan2 {
	    public static void main(String[] args) {
	        
	    	System.out.println("学生信息：");
	        Student zs = new Student();
	        zs.setName("张三");
	        zs.setAge(21);
	        zs.setNumber(2019310123);
	        System.out.println("姓名:" + zs.getName());
	        System.out.println("年龄:" + zs.getAge());
	        System.out.println("学号:" + zs.getNumber());

	        System.out.println("教师信息：");
	        Teacher ls = new Teacher();
	        ls.setName("李四");
	        ls.setNumber(00000001);
	        ls.setSex("女");
	        ls.setLesson_1("java技术及应用");
	        System.out.println("教师:" + ls.getName());
	        System.out.println("工号:" + ls.getNumber());
	        System.out.println("教师性别:" + ls.getSex());
	        System.out.println("课程信息：");
	        Lesson_1 java = new Lesson_1();
	        java.setName("java技术及应用");
	        java.setTime("1-12周 周一 上午7:50-11:15");
	        java.setNumber(000001);
	        java.setPlace("教学楼 101");
	        System.out.println(java.toString());

	        System.out.println("选课成功");

	    }

	}
'''

## 实验结果
学生信息：
姓名:张三
年龄:21
学号:2019310123
教师信息：
教师:李四
工号:1
教师性别:女
课程信息：
课程名称：java技术及应用
上课时间：1-12周 周一 上午7:50-11:15
课程编号：1
授课地点：教学楼 101

选课成功

## 实验感想
通过这次实验，我大致掌握了类的继承用法，和super（）等方法的用法，并基本上自主完成了实验，虽然实验过程因为自身水平不到位磕磕绊绊的，最后还是按要求完成了实验。
提交后我会再根据不足和以后对代码的理解再加深之后再对程序进行修改和完善。
