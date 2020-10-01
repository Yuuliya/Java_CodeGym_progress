# Java_CodeGym_progress
This is to track my progress at CodeGym. 


package com.codegym.task.task02.task0217;

/* 
Minimum of four numbers

*/
public class Solution {
            public static int min(int a, int b, int c, int d) {
    int m, n;
    m = min(a, b);
    n = min(c, d);
    return min(m, n);
    
           }
      public static int min(int a, int b) {
        //
        int f;
        if (a <= b) 
            f = a;
         else 
            f = b;
            
        
            return f;
    }

    public static void main(String[] args) throws Exception {
        System.out.println(min(-20, -10));
        System.out.println(min(-20, -10, -30, -40));
        System.out.println(min(-20, -10, -30, 40));
        System.out.println(min(-40, -10, -30, 40));
    }
}
