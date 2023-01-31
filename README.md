import java.util.Scanner;

public class task {

	public static void main(String[] args) {
		 studentsArray ();
		 whileLoop();
		 System.out.println();
		 DowhileLoop();
		 System.out.println();
		 ForLoop();
		 System.out.println();
		 Stars() ;
		
	    
	
	}
	
	
	 public static void studentsArray () {
			String [] [] students = {
					
					{"Jo","50","F","oh!!!!"},
					{"Ehab","90","A","Excellent Job"},
					{"Smith","80","B","Great Job"}
			                                           };
			
			for (int i = 0; i <= 2; i++) {
				
				for (int j = 0; j < 4; j++) {
					System.out.print(students[i][j]+ "  ");
				}
				System.out.println();
			}
			}
	 
	 public static void whileLoop() {
			
				int i = 1 ;
				while(i<= 100)  
				{  if(i%2!=0) {
				 System.out.print(i + "  ");
				 }
				i++; 
				}     
				
				}
	 
	 public static void DowhileLoop() {
		
		 int i = 1;
			    do 
			    {
			        if ( i % 2 != 0 ) {
			         System.out.print(i + "  ");
			        }

			        i++;
			    } while (i <= 100 );
			    
	 }
	 public static void ForLoop() {
		int number=100;  
		for (int i=1; i<=number; i++)   
		{   
		  if (i%2==0)   
		{  
		System.out.print(i + " ");  
		}  
		}  	
		 
	}
	 
	 
	public static void Stars() {
		int num;
        System.out.println("Enter the integer: ");
        Scanner s = new Scanner(System.in);
        num = s.nextInt();
        System.out.println("Entered integer is: "	+ num);
    
		for (int i = 1; i <= num; ++i) {  

		for (int j = 1; j <= i; ++j) { 

		System.out.print("* "); 

		}

		System.out.println(); 

		}

		}

		
 
}
