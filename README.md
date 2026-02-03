# javaproblem-solving-for3
//display 10 numbers by printing three numbers in a line separated by commas.
import java.util.Scanner;
class Nums{
    public static void main(String[] args) {
       Scanner sc=new Scanner(System.in);
       int num;
       System.out.println("asking ten numbers from user...!");
       for(int i=1;i<=10;i++){
                num=sc.nextInt();
               System.out.print(num);
           if(i%3==0){
               System.out.println();
           }else if(i!=10){
               System.out.print(",");
           }
       }
    }
}
