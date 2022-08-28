import java.util.*;
public class maximum{
public static void main(String args[]){
int[] a;
a=new int[10];
Scanner obj=new Scanner(System.in);
System.out.println("enter the no of elements : ");
int n=obj.nextInt();
for(int i=0;i<n;i++){
System.out.print("enter the num "+i +" : ");
a[i]=obj.nextInt();
}
int c;
for(int j=0;j<n;j++){
for(int k=j+1;k<n;k++){
if(a[j]>a[k]){
c=a[j];
a[j]=a[k];
a[k]=c;
}
}
}
System.out.println("enter the m value : ");
int m=obj.nextInt();
System.out.println("enter the n value : ");
int n1=obj.nextInt();
System.out.println("mth maximum value : "+a[n-m]);
System.out.println("nth minimum value : "+a[n1-1]);
int sum=a[n-m]+a[n1-1];
int sub=a[n-m]-a[n1-1];
System.out.println("sum : "+sum);
System.out.println("difference : "+sub);
}
}
