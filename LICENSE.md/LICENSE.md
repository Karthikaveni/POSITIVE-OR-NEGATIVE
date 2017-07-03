import java.io.*;
import java util.*;
public class Main{
public static void main(String args[])
{
BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
int a;
a=Integer.parseInt(br.readLine());
if(a==0)
System.out.println("POSITIVE");
else 
if(a>0)
System.out.println("NEGATIVE");
}
}
