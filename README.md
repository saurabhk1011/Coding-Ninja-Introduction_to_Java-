# Coding-Ninja-Introduction_to_Java-
Write a program to input name (as a single character) and marks of three tests of a student (all integers). Then calculate and print the name and average (integer) of all test marks. All the test marks are integers and calculate average also as integer. That is, you need to print the integer part of average only, neglect the decimal part.
import java.util.Scanner;
public class Solution {


	public static void main(String[] args) {
		
		/* Your class should be named Solution.
	 	* Read input as specified in the question.
	 	* Print output as specified in the question.
		*/
        Scanner in = new Scanner(System.in);
		String str = in.next();
		int m1 = in.nextInt();
        int m2 = in.nextInt();
        int m3 = in.nextInt();
        int avg = (m1 + m2 + m3) / 3 ;
        
        System.out.println(str);
            System.out.println(avg);
        
	}

}
