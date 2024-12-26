package app;

public class Main  {
    static String Product;
    static int day;
    static double day1;
    static double day2;
    static double day3;
    static double day4;
    static double day5;
    static double day6;
    static double day7;
    static double EUR;
    static double sales;
    static double rounded;

    public static void main(String[] args) {
        Product = "smartphone";
        day = 5;
        day1 = 10000.99;
        day2 = 10200.59;
        day3 = 6000.39;
        day4 = 8000.25;
        day5 = 3000.10;
        EUR = day1+day2+day3+day4+day5;
        sales = EUR/day;;
        rounded = Math.round(sales * 100.00) / 100.00;
        System.out.println("Product No 1: " + Product);
        System.out.println("total sales for " + day + " days is EUR " + EUR);
        System.out.println("sales by day is EUR " + rounded + ".");

        System.out.println( );

        Product = "laptop";
        day = 7;
        day1 = 15000.00;
        day2 = 13200.00;
        day3 = 4000.00;
        day4 = 3000.99;
        day5 = 9000.00;
        day6 = 8000.00;
        day7 = 4000.00;
        EUR = day1+day2+day3+day4+day5+day6+day7;
        sales = EUR/day;;
        rounded = Math.round(sales * 100.00) / 100.00;
        System.out.println("Product No 2: " + Product );
        System.out.println("total sales for " + day + " days is EUR " + EUR);
        System.out.println("sales by day is EUR " + rounded + ".");
         }
}
