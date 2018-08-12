# Threading-main-and-child-
class Mythread extends Thread
{
 public void run()
{
 for(int i=0;i<5;i++)
{
 System.out.println("CHILD THREAD");
}
}
  public static void main(String args[])
{
 Mythread obj=new Mythread();
 obj.start();
for(int i=0;i<5;i++)
{
 System.out.println("MAIN THREAD");
}
}
}
