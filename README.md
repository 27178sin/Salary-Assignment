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
   
   //
   double rate = 10.75;
  
   //
   double week = 52;
  
   //
   double month = 12;
  
   //
   double Incometax = 0.15;
   
   //
   double El = 1.66;
   
   //
   double CPP = 4.95;
   
   //Weekly Rate
   double w = rate*hours;
     
   //Monthly Rate
   double m = w*week/month;
   
   //Annual Rate
   double a = m*month;

   //Weekly Rate
   System.out.println("Weekly Rate=hours multiplied by rate\n" +rate+ "*" +hours+ "=" + w );
    
   //Monthly Rate
   System.out.println("Monthly Rate=w multiplied by week divided by month\n" +w+ "*" +week+ "/" +month+ "=" + m );
     
   //Annual Rate
   System.out.println("Annual Rate=m multiplied by month\n" +m+ "*" +month+ "=" + a );
   
    }
  }
