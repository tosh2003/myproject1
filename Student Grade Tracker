import java.util.Scanner;
public class codealpha1 {
    public static void main(String[] args) {
        int arr[] = new int [5];
        grade(arr);
    }
    static void grade (int arr[]){
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the marks");
        for(int i = 0 ; i < arr.length ; i++){
            arr[i] = sc.nextInt();
        }
        int max = Integer.MIN_VALUE;
        int min = Integer.MAX_VALUE;
        int sum = 0;
        for(int  i = 0 ; i < arr.length ; i++){
            sum = sum + arr[i];
            if(arr[i] < min){
                min = arr[i];
            }
            if(arr[i] > max){
                max = arr[i];
            }

        }
        float average = sum / arr.length;
        System.out.println("Average marks is "+average);
        System.out.println("Highest marks is "+max );
        System.out.println("Lowest marks is "+min);
        


        

    }
}
