# Pattern-Character
import java.util.Scanner;
class Pattern
{
    public static void main(String args[])
    {
        int n =5,i,j;
        char ch='A';
        for(i=0;i<=n-1;i++)
        {
            for(j=0;j<=i;j++)
            {
                System.out.print(ch+ " ");
                ch++;
            }
            System.out.println();
        }
    }
}
