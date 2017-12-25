
import java.io.*;
 
public class Denominations{
public static void main(String[] args) {
	int a,b,c,d,f,g,h;
	Object Amount;
 
	try{
	
	BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
	System.out.println("enter the amount of money");
	int n = 0;
	try {
		n = Integer.parseInt(br.readLine());
	} catch (NumberFormatException e) {
		e.printStackTrace();
	} catch (IOException e) {
		e.printStackTrace();
	}
	
	a=n/500;
	System.out.println("number of 500 rupees notes: "+a);
	n=n%500;
	b=n/100;
	System.out.println("number of 100 rupees notes: "+b);
	n=n%100;
	c=n/50;
	System.out.println("number of 50 rupees notes: "+c);
	n=n%50;
	d=n/20;
	System.out.println("number of 20 rupees notes: "+d);
	n=n%20;
	f=n/10;
	System.out.println("number of 10 rupees notes: "+f);
	n=n%10;
	g=n/5;
	System.out.println("number of 5 rupees notes: "+g);
	n=n%5;
	h=n/2;
	System.out.println("number of 2 rupees notes: "+h);
	n=n%2;
	System.out.println("number of 1 Rupee notes: "+n);
	}
    finally {
} 
}
	void Catch(IOException e){
		System.out.println("error in input");
		}
 
	}
