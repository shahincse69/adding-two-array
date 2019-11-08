# adding-two-array
public class Main
{
	public static void main(String[] args) {
	    int[]a={1,2,3,4,5};

        int b[]={6,7,8,9,10};

        int c[]=new int[a.length];

    for(int i=0;i<=a.length-1;i++) {

        c[i]=a[i]+b[i]; //ADDING

    }

    System.out.println("SUM OF TWO ARRY");

    for( int j=0;j<=c.length-1;j++) {

    System.out.println(c[j]); //DISPLAYING

    }

    }

}
