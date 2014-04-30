DICE-LAB-1-WEEK-11
==================

DICE LAB #1 WEK #11  


// BY REINA OLARTE

// DICE LAB # 1   WEEK 11


public class Dice
{
	
	//  VARIABLE
	
	int CompNumber;	
	
	public int Throw()	
	
	{				
		CompNumber = (1	 + (int)(Math.random() * 6));	
		
		
		System.out.printf("The number of the computer  was %d\n", CompNumber);	
		
		return CompNumber;	
		
		}	
	public void Value()	
	
	{		
		System.out.printf("The Number rolled from the dice was : %d\n", CompNumber);	
		
		
		}		// END METHOD
	}			// END CLASS
