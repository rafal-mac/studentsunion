import sheffield.*;
public class ExeC {
	public static void main (String[] args) {
		EasyReader keyboard = new EasyReader();
		
		int[] first = new int[5];
		int[] second = new int[5];
		

		for (int i=0; i<first.length; i++)
			first[i] = keyboard.readInt(
				"Enter the value " + i + " of list 1 : ");

			
		for (int i=0; i<second.length; i++)
			second[i] = keyboard.readInt(
				"Enter the value " + i + " of list 2 : ");
		
		int lol = 0;
		for (int i=0; i<first.length; i++) {
			for (int j=0; j<second.length; j++) {
				if ( first[i]==second[j] )
					lol++;
					second[j]=0;
			}			
		}
		
		if ( lol==5 )
			System.out.println("The two lists have the same content");
		else
			System.out.println("no");
	}
}