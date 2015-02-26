# Search
searches for values and returns index
import javax.swing.JFrame;


public class Search extends JFrame {
	
	public static void main (String args[]){
		
		int[] data = {1,2,3,4,5};
		int size = data.length;
		
		for (int i=0; i<size; i++){
			if(data[i]==8)
			System.out.println(i);
			
			
		}
		
	}

}
