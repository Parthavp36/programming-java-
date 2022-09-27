import java.util.*;
public class dk{
public static void main(String args[]){
Scanner obj=new Scanner(System.in);
int y1;
System.out.print("enter the date : ");
int d=obj.nextInt();
System.out.print("enter the month : ");
int m=obj.nextInt();
if(m==1 || m==10)
m=0;
else if(m==2 || m==3 || m==11)
m=3;
else if(m==4 || m==7)
m=6;
else if(m==5)
m=1;
else if(m==6)
m=4;
else if(m==8)
m=2;
else if(m==9 || m==12)
m=5;
System.out.print("enter the year : ");
int y=obj.nextInt();
y1=y;
if(y<2000)
y=y%100;
else
y=y-1900;
int lp=y/4;
System.out.println(y);
int days=(d+m+y+lp)%7;
if(days==1)
System.out.println("mon");
else if(days==2)
System.out.println("tue");
else if(days==3)
System.out.println("wed");
else if(days==4)
System.out.println("thurs");
else if(days==5)
System.out.println("fri");
else if(days==6)
System.out.println("sat");
else
System.out.println("sun");
}
}
