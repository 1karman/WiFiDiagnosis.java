# WiFiDiagnosis.javaimport java.util.Scanner;

	
public class WiFiDiagnosis {
	
	public static void main(String[] args) {
		
		/*
		 * Class: CMSC203 
		 * Instructor:
		 * Description: (Give a brief description for each Class)
		 * Due: 2/08/2021
		 * Platform/compiler:
		 * I pledge that I have completed the programming assignment independently.
		   I have not copied the code from a student or any source.
		   I have not given my code to any student.
		   Print your Name here: Arman Moutanabbih
		*/
		
		
		String answer;
		System.out.println("Reboot the computer and try to connect");
		System.out.println("Did that fix the problem? (yes/no)");
		
		Scanner user = new Scanner(System.in);
		
		answer = user.nextLine();
	
		//reads user input
		if("no".equals(answer)) {
			System.out.println("Reboot the router and try to connect");
			
			System.out.println("Did that fix the problem? (yes/no)");
			answer = user.nextLine();
			
			if("no".equals(answer)) {
				System.out.println("Make sure the cables connecting the router are firmly plugged in and power is getting to the router");
				System.out.println("Did that fix the problem? (yes/no)");
				answer = user.nextLine();
				
				if("no".equals(answer)) {
					System.out.println("Move the computer closer to the router and try to connect");
					
					System.out.println("Did that fix the problem? (yes/no)");
					answer = user.nextLine();
					
					if("no".equals(answer)) {
						System.out.println("You will need to contact your ISP");

					}
				}

				
			}

		}

		}

	
}
