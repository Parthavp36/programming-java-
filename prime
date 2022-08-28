import java.util.Scanner;
public class prime{
public static void main(String args[]){
int[] p;
p=new int[10];
int pr=0;
int com=0;
Scanner obj=new Scanner(System.in);
System.out.println("enter the no of elements: ");
int n=obj.nextInt();
for(int i=0;i<n;i++){
System.out.println("enter the num "+i );
p[i]=obj.nextInt();
int c=0;
for(int j=2;j<=p[i];j++){
if(p[i]%j==0){
c++;
}
}
if(c==1){
pr++;
}
else{
com++;
}
}
System.out.println("no of prime numbers : "+pr);
System.out.println("no of composite numbers : "+com);
}
}
