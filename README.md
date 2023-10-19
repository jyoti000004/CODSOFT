import java.util.Random
import java.util.Scanner; 
public class numbergame
{

public static void main(String[] args)
{
Random rand new Random(); 
int randomnumber = rand.nextInt(bound:100)+1;
System.out.println("Random number is + randomnumber);
System.out.println(x:"Enter your guess (1-100)"); 
Scanner sc=new Scanner(System.in);
int playerguess = sc.nextInt();
if (playerguess randomnumber)
{
System.out.println(x:"Correct! You win");
} 
else if(randomnumber > playerguess)
{
System.out.println(x:"Nope! The number is high.Guess again"); 
}
else{
System.out.println(x:"Nope! The number is low.Guess again");
}
}
}
