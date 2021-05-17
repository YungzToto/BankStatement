//Basic Bank Statement
public class BankStatement
{
  public static void main(String args[])
  {
     //Creating a variable to store bank balance
     double balance = 156.45;
     
     //Check how much is in account
     if(balance < 0)
     {
       System.out.println("Sorry.");
       System.out.println("Your account is overdrawn");
       }
     else
     {
       System.out.println("Your balance is €400");
       }
    }
}
