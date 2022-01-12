# Java Assessment Question 3

## Task 1

import java.util.*;
public class main{
    public static boolean isUnique(int[] a)
    {
        if (a.length<=0)
    
    System.out.println("NOElementsInArrayException");
    }
    if(list.length<=1)
    return true;
    
    for(int i=0;i<list.length-1;i++){
        if(list[i]>list[i+1])
        return false;
    }
    return true;

    public satic void main(String[] args){
        Scanner sc= new Scanner(System.in);
        int n=sc.nextint();
        int a[]=new int[n];
        double list[]=new double[n];
        for(int i=0;i<n;i++){
            a[[i]=sc.nextint();
        }
        for(int i=0;i<n;i++){
            list[i]=sc.nextdouble();
        }
        
        System.out.println(Main.isUnique(a));
        System.out.println(Main.isSorted(list));


}