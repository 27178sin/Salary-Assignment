# Salary-Assignment
//In Class Salary Assignment
/*
 * Luke Sinclair
 * Mrs.McCaffery
 * ICS3*U
 * Description-We are creating a salary calculator to calculate the weekly pay, monthly pay, annual pay, store these in variable 
 */

public class SalaryAssignment
{
  public static void main (String[]args)
  {
   //Declaring variables
   
   double hours = 30; 
   
   //rate
   
   double rate = 10.75;
  
   //week
   
   double week = 52;
  
   //month
   
   double month = 12;
  
   //incometax
   
   double incometax = 1.15;
   
   //EL Tax
   
   double el = 1.0166;
   
   //CPP Tax
   
   double cpp = 1.0495;
   
   //Weekly Rate
   
   double w = rate*hours;
     
   //Monthly Rate
   
   double m = w*week/month;
   
   //Annual Rate
   
   double a = m*month;
   
   //Amount of Annual Rate taken by incometaxes
   
   double it = a*incometax-a;
   
   //Amount of Annual Rate taken by EL
   
   double y = a*el-a;
   
   //Amount of Annual Rate taken by CPP
   
   double x = a*cpp-a;
   
   //Annual Rate including Taxes
   
   double ar = a-it-y-x;
//Print Statements
   
   //Weekly Rate
   
   System.out.println("Weekly Rate=hours multiplied by rate\n" +rate+ "*" +hours+ "=" + w );
    
   //Monthly Rate
   
   System.out.println("Monthly Rate=w multiplied by week divided by month\n" +w+ "*" +week+ "/" +month+ "=" + m );
     
   //Annual Rate
   
   System.out.println("Annual Rate=m multiplied by month\n" +m+ "*" +month+ "=" + a );
   
   //Annual Rate including Taxes
   
   System.out.println("Annual Rate with Taxes=a subtracted by it subtracted by y subtracted by x\n" +a+ "-" +it+ "-" +y+ "-" +x+ "=" ar);
   
   //close main
   
   }
   
   //close class
   
   }
   
   
   
   
