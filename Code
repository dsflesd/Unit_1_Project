import java.util.Scanner;
public class Main
{
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        System.out.print("Enter the total bill: ");
        double totalBill = scan.nextDouble();
        System.out.print("Enter the tip percentage: ");
        int tipPercentage = scan.nextInt();
        System.out.print("Enter number of people: ");
        int numberOfPeople = scan.nextInt();
        double totalTipAmount = (double)totalBill* (int)tipPercentage/100;
        double totalBillWithTips = (totalTipAmount+totalBill);
        double tipPerPerson =  totalTipAmount/ numberOfPeople;
        double totalPerPerson =  totalBillWithTips/numberOfPeople;
        totalBillWithTips = Math.round(totalBillWithTips*100)/100.0;
        tipPerPerson = Math.round(tipPerPerson*100)/100.0;
        totalPerPerson = Math.round(totalPerPerson*100)/100.0;
        System.out.printf("Total Tip Amount: $" + "%.2f%n", totalTipAmount);
        System.out.printf("Total Bill With Tips $" + "%.2f%n", totalBillWithTips);
        System.out.printf("Tip Per Person: $" + "%.2f%n", tipPerPerson);
        System.out.printf("Total Per Person: $" + "%.2f%n", + totalPerPerson);
        scan.nextLine();
        scan.close();
    }
}
