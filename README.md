import java.util.Scanner;
public class ifelse {
    public static void main(String[] args) {

   Scanner input =new Scanner(System.in);
   int num;
        System.out.print("Enter a digit between 0-9 :");
        num = input.nextInt();
        if(num>0){
            System.out.println("posetive");
        }
        else {
            System.out.println("Negative");

        }

    }
}
