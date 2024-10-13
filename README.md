//Code in Java:


package journal.pkg4b;

public class Journal4B 
{
    public static void getFizzBuzz(int number)
    {
        if (number % 3 == 0) 
        {
            System.out.println("fizz");
        }
        else if (number % 5 == 0) 
        {
            System.out.println("buzz");
        }
        else if (number % 3 == 0 && number % 5 == 0) 
        {
            System.out.println("fizzbuzz");
        }
    }
    public static void main(String[] args) 
    {
        for (int i = 1; i <= 100; i++) 
        {
            System.out.println(i);
            getFizzBuzz(i);
        }
    }
    
}
