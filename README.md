public class SumAverageRunningInt { 
   public static void main (String[] args) {
     
      int sum = 0;          
      double average;       
      int lowerbound = 111;
      int upperbound = 8899;

      
      for (int number = lowerbound; number <= upperbound; ++number) {
          
         sum += number;     
      }
      
      average = (double) sum / (double) (upperbound - lowerbound + 1);
      
      System.out.println("Sum: " + sum + " Average: " + average);
   }
}
