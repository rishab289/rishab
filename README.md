import java.util.Scanner;
class abst3{
public static void main(String[]args){        
int x,l;
Scanner a1=new Scanner(System.in);
System.out.print("Enter a Number :");
x=a1.nextInt();
l=x;
String a=String.valueOf(x);
int n=a.length();
String s=new String();
for(int i=0;i<n;i++){
int l1=l%10;
l=l/10;
s=s+String.valueOf(l1);
}
if(s.equals(a)){
 System.out.println("no. is palindrom");
}
else{
 System.out.println("no. is not palindrom");
}
}
}
