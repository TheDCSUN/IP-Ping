import java.net.*;
import java.util.Scanner;
public class Network_Test {

	public static void main(String[] args) throws UnknownHostException {
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter website name : ");
		String n = sc.nextLine();
		System.out.println("Enter website URL : ");
		String s = sc.nextLine();
		try{
			InetAddress ip = InetAddress.getByName(new URL(s).getHost());
			System.out.println(" The IP Address of " +n+ " is "+ ip);
			
		}
		catch(MalformedURLException e)
		{
			System.out.println(" Wrong URL! ");
		}
		
		sc.close();
	}

}
