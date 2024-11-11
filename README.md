import java.util.*;
public class Main 
{
    public static void main (String[] args) 
    {
        Scanner s=new Scanner(System.in);
        for(int i=s.nextInt();i>0;System.out.print((int)Math.sqrt(i)),i=i-((int)Math.sqrt(i)*(int)Math.sqrt(i)));
        
    }
}
