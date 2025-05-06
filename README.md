# sum-of-100-natural-no.-without-Loop
//sum of first 100 natural numbers
public class Main {
// making a function
    public static void printSum(int i, int n, int sum){
       //make base case
        if(i==n){
            sum+=i;
            System.out.println(sum);
            return;
        }
        sum+=i;
       //recursive function
        printSum(i+1,n,sum);
    }
    //main function
    public static void main(String[] args) {
        printSum(1,100,0);
    }

    }


