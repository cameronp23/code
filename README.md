import java.util.*;
import java.util.Scanner;
public class Lesson_7_Activity_One {
    public static void main(String[] args){
        int number;
        Scanner keyboard = new Scanner (System.in);
        System.out.println ("Please enter an integer with up to 3 digits.");
        number = keyboard.nextInt( );

        System.out.println (number / 100);
        number = number % 100;
        System.out.println (number / 10);
        System.out.println (number % 10);
        System.out.println ( );
    }
}
