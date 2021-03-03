# cse360-A1
 branch2



/***** * Ali Aldulaimi. ******/
public class GitDemo {
    private double previousNumber;
    private double reverseNum;

    // constructor
    public GitDemo() {
        previousNumber = 1;
    }

    /*****
     *
     * This function should add 'num' to 'previousNumber' and return the sum.
     *
     *****/
    public double addNumber(double num) {
        System.out.print("Add num to previousNumber");
        previousNumber = previousNumber + num;
        return previousNumber;

    }

    /*****
     *
     * This function should calculate the factorial of 'num' and return the
     * resulting value.
     *
     * i.e. if num = 4,
     *
     * the function will return the value of (1 * 2 * 3 * 4)
     *
     *****/

    public double findFactorial(double num) {
        double newNumber = 1;
        for (int i = 1; i <= num; ++i) {

            newNumber = newNumber * i;

        }
        reverseNum = newNumber;
        return newNumber;
    }

    /*****
     *
     * This function should reverse 'num' and return the resulting value.
     *
     * i.e. if num = 1234
     *
     * the function will return 4321
     *
     *****/

    public int reverseNumber(int num) {

        int factorialNumber = 0;

        while (num != 0) {

            int temp = num % 10;

            factorialNumber = factorialNumber * 10 + temp;

            num /= 10;
        }

        return factorialNumber;

    }

}

Ali Aldulaimi
W class


/***** * Ali Aldulaimi. ******/
public class GitDemo {
    private double previousNumber;
    private double reverseNum;

    // constructor
    public GitDemo() {
        previousNumber = 1;
    }

    /*****
     *
     * This function should add 'num' to 'previousNumber' and return the sum.
     *
     *****/
    public double addNumber(double num) {
        System.out.print("Add num to previousNumber");
        previousNumber = previousNumber + num;
        return previousNumber;

    }
    

  
