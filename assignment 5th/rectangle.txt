package assignment4;
import java.util.Scanner;
public class Rectangle {
int length;
int breadth;
public int CalculateArea()
{
    int l,b;
    l=this.length;
    b=this.breadth;
    return l*b;
}
public static void main(String[] args)
{
    Rectangle obj=new Rectangle();
    Scanner sc=new Scanner(System.in);
    System.out.print("Enter length ");
    obj.length=sc.nextInt();
    System.out.print("Enter breadth ");
     obj.breadth=sc.nextInt();
     sc.close();
   System.out.println("Area is "+obj.CalculateArea());
}
}