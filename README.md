# multi-thread-java-
import java.util.random;
class thread1 extends threas
{
int i,n;
random r=new random();
public void run()
{
for(i=0;i<5;i++)
{
system.out.println("thread 1 generates:"+n);
int n=nextInt(r);
if(n%2==0)
{
thread t2=new thread 2(n);
t2.start();
}
else
{
thread t3=new thread 3(n);
t3.start();
}
}
class thread2 extend thread
{
int n;
thread2(int n)
{
this.n=n;
}
public void run()
{
system.out.println("thread 2 generates:"+n*n);
}
}
class thread's extend thread
{
int n;
thread's(int n)
{
this.n=n;
}
public void run()
{
system.out.println("thread's generates:"+n*n*n);
}
}
public class thread
{
public static void main(string[]args)
{
thread t1=new thread 1();
t1.start;
}
}


