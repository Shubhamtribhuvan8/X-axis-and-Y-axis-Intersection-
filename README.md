# X-axis-and-Y-axis-Intersection-
Give the Input X and Y you get intersection point!!!
import java.util.*;
import java.util.Scanner;
class HelloWorld {
    public static void main(String[] args) {
       int[][] arr=new int[][]  { {0,0,0,0,0,0,0,0,0,0,0},
                                  {0,1,8,4,3,1,8,1,6,7,10},
                                  {0,0,1,1,2,4,9,0,5,0,1},
                                  {0,1,0,4,1,3,1,1,0,8,4},
                                  {0,0,5,5,6,7,2,0,7,4,3},
                                  {0,5,7,6,9,8,0,3,3,0,2},
                                  {0,4,6,8,8,0,3,4,1,1,1},
                                  {0,3,8,9,0,9,4,5,4,8,0},
                                  {0,2,1,0,9,1,5,6,5,9,1},
                                  {0,6,0,1,8,0,1,7,8,8,2},
                                  {0,0,0,0,7,1,0,9,9,7,1}};
int n=arr.length;
int m=arr[0].length;
    for(int i=0;i<n;i++)
    {
        for(int j=0;j<m;j++)
{
    Scanner sc=new Scanner(System.in);
    int p=sc.nextInt();
    int q=sc.nextInt();
    System.out.print(arr[q][p]);
}
}
}
}

