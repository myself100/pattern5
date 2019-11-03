# pattern5

import java.util.Scanner;
public class pattern {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
        Scanner s=new Scanner(System.in);
		int n=s.nextInt();
		
		for(int i=1;i<=n;i++) {
		   int k=1;
			for(int j=i;j>=1;j--) {
				System.out.print(k);
				k--;
				if(k<0) {
					k=1;
				}
			}
			System.out.println();
		}
	}
}


output ::                   ///when n is 6
6
1
10
101
1010
10101
101010
