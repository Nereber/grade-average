# grade-average
package Kafa;
import java.util.Scanner;

public class Kelle {
    public static void main(String[] args) {
  //Creating the Variables
        int biology,math,physics,music;

        //I created Scanner Class
        Scanner abc=new Scanner(System.in);
        //Get value from users
        System.out.print("My Biology Grade:");
       biology=abc.nextInt();

        System.out.print("My Physics Grade:");
        physics=abc.nextInt();
        System.out.print("My Math Grade:");
        math=abc.nextInt();

        System.out.print("My Music Grade:");
        music=abc.nextInt();

        int total= math+biology+music+physics;
        double result= total/4;
        System.out.println(result);

        boolean c1=result>70.0;

        String family=c1 ? "pass the class" : "pass not the class";
        System.out.println(family);
