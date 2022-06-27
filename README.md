import java.util.Scanner;
class calculator
{
   Public static void main(String[] args)
   {
     Scanner.s=new Scanner(system.in) 
     System.out.println("enter your first no=")
     int no1=s.nextint();
     System.out.println("enter your second no=");
     int no2=s.nextint();
     System.out.println("select symbol(+,-,*,/));
     String symbol=s.next();
     int result;
       
      Switch(symbol)
     {
        case"+":result=no1+no2;
        System.out.println("addition is="+result)
        Break;
        
        case"-":result=no1+no2;
        System.out.println("subtraction is="+result)
        break;
       
        case"*":result=no1*no2;
        System.out.println("multyply is="+result);
        break;

        case"/":result=no1/no2;
        System.out.println("divide is="+result);
        break;
        
        default:
        System.out.println("invalid syntax"); 

     }


   } 

}
