# cse360-A1


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
    

  
