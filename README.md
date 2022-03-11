# this-keyword
class Student
{
    int a,b,c;
    Student(int a,int b,int c)
    {
        this.a=a;
        this.b=b;
        this.c=c;
    }
    void display()
    {
        System.out.println("the value of a is"+a);
        System.out.println("the value of b is"+b);
        System.out.println("the value of c is"+c);
    }
}
class Main 
{
    public static void main(String args[])
    {
        Student s1=new Student(11,22,33);
        s1.display();
    }
}
    
