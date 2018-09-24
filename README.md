# Linear-Search-

public class Linearsearch {
	LinearSearch(int numbers, int numbersSize, int key); {
		   int i = 0;

		   for (i = 0; i < numbersSize; ++i)
		      if (numbers[i] == key) {
		         return i
		      }
		   }
		      
		   return -1 // not found
				   
	public static void main(String[] args) {
		// TODO Auto-generated method stub
			  numbers = {2, 4, 7, 10, 11, 32, 45, 87}
			  double NUMBERS_SIZE = 8;
			   i = 0;
			   int key = 0;
			   int keyIndex = 0;
			      
			   System.out.println("NUMBERS: ");
			   for (i = 0; i < NUMBERS_SIZE; ++i) {
			     System.out.println(numbers[i] + " ");
			   }
			   System.out.println();
			      
			   System.out.println("Enter a value: ");
			   key = getIntFromUser()
			      
			   keyIndex = LinearSearch(numbers, NUMBERS_SIZE, key)
			      
			   if (keyIndex == -1) {
			     System.out.println(key + " was not found.");
			   } 
			   else {
			      System.out.println("Found " + key + " at index " + keyIndex + ".");
			   }
		   
	}

}
