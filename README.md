# oddnumber

package com.vishnu.jsp;

public class SumOfOddNUmbers {
    public static void main(String[] args) {
        int start = 7;
        int end = 21;
        int sum = 0;

        System.out.println("Odd numbers between " + start + " to " + end + " is: " + sum);
        for (int i = start; i <= end; i++) {
            if (i % 2 != 0) {
                sum += i;
            }
        }

        System.out.println("\nSum of number:"+ sum);
    }
}





output
Odd numbers between 7 to 21 is: 0

Sum of number:112


Sum of number:112
