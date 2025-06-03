TAKING INPUT IN JAVA:

import java.util.*;
public class Hello {
    public static void main(String[] args) {
        int a,b,sum;
        Scanner sc= new Scanner(System.in);
        a= sc.nextInt();
        b= sc.nextInt();
        sum=a+b;
        System.out.print(sum);
        sc.close();

    }
}

ARRAYS IN JAVA:

import java.util.*;
public class Arrays{
    public static void main(String[] args) {

        //taking input for the size of array
        System.out.println("enter the size of array: ");
        Scanner sc= new Scanner(System.in);
        int size=sc.nextInt();
        int[] numbers= new int[size];

        //taking input of array values
        System.err.println("enter the values of array: ");
        for(int i=0; i<size; i++){
            numbers[i]=sc.nextInt();        
        }

        //taking the value to be found
        System.out.println("enter the number you want to find the index of:");
        int num =sc.nextInt();

        //finding the index

        for(int i=0;i<size; i++){
            if(num==numbers[i]){
                System.out.println("the number was found on index: "+ i);
            }
        }
    }
}

2D ARRAYS IN JAVA:

EXAMPLE 1:
import java.util.*;
public class twodArrays{
    public static void main(String[] args) {
        Scanner sc= new Scanner(System.in);
        //input the size of 2d array
        int rows=sc.nextInt();
        int cols=sc.nextInt();
        int[][] numbers=new int[rows][cols];
        //enter values of 2d array
        for(int i=0; i<rows;i++){
            for(int j=0;j<cols;j++){
                numbers[i][j]=sc.nextInt();
            }
        }
        //output the 2d array
        for(int i=0;i<rows;i++){
            for(int j=0;j<cols;j++){
                System.out.print(numbers[i][j] +" ");
            }
            System.out.println();
        }
    }
}

EXAMPLE 2:

import java.util.*;
public class twodArrays{
    public static void main(String[] args) {
        Scanner sc= new Scanner(System.in);
        //input the size of 2d array
        System.out.println("enter the number of rows: ");
        int rows=sc.nextInt();
        System.out.println("enter the number of columns: ");
        int cols=sc.nextInt();
        int[][] numbers=new int[rows][cols];
        System.out.println("enter the values of 2d array");
        //enter values of 2d array
        for(int i=0; i<rows;i++){
            for(int j=0;j<cols;j++){
                numbers[i][j]=sc.nextInt();
            }
        }
        //input the value of x
        System.out.println("enter the value of x to find the indexes: ");
        int x=sc.nextInt();
        //output the 2d array
        for(int i=0;i<rows;i++){
            for(int j=0;j<cols;j++){
                if(numbers[i][j]==x){
                System.out.print("x found at index:("+i+","+j+")");
                }
            }
            System.out.println();
        }
    }
}

BUBBLE SORT IN JAVA:

EXAMPLE 1:
import java.util.Random;

public class BubbleSort {
  public static void main(String[] args) {

    Random rand = new Random();
    int[] n= new int[10];
    
    for (int i = 0; i < n.length; i++) {
      n[i] = rand.nextInt(20);
    }
    
    System.out.println("Before:");
    printArray(n);
    
    //Sorting algorithm here
    boolean swappedSomething = true;
    
    while (swappedSomething) {
      swappedSomething = false;
      
      for (int i = 0; i < n.length - 1; i++) {
        if (n[i] > n[i + 1]) {
          swappedSomething = true;
          int temp = n[i];
          n[i] = n[i + 1];
          n[i + 1] = temp;
        }
      }
    }

    
    System.out.println("\nAfter:");
    printArray(n);
  }

  private static void printArray(int[] numbers) {
    for (int i = 0; i < numbers.length; i++) {
      System.out.print(numbers[i]+" ");
    }
  }
}

EXAMPLE 2:

import java.util.*;
public class BubbleSort {
    public static void main(String[] args) {
        Scanner sc= new Scanner(System.in);

        System.out.println("enter the size of array");
        int size=sc.nextInt();
        int[] n=new int[size];

        System.out.println("enter the values: ");
        for(int i=0;i<n.length;i++){
            n[i]=sc.nextInt();
        }

        System.out.println("before bubble sort:");
        for(int i=0;i<n.length;i++){
            System.out.print(n[i]+" ");
        }
        System.out.println();
         boolean swappedSomething =true;
        //[1,2,3,4,5]
        // 0 1 2 3 4 
         while (swappedSomething) {
            swappedSomething=false;
            for(int i=0;i<n.length-1;i++){
                if(n[i]>n[i+1]){
                    swappedSomething=true;
                    int temp=n[i];
                    n[i]=n[i+1];
                    n[i+1]=temp;
                }
            }
         }
         System.out.println("after bubble sort:");
        for(int i=0;i<n.length;i++){
            System.out.print(n[i]+" ");
        }
    }
    
}

INSERTION SORT IN JAVA:

EXAMPLE 1:
import java.util.Random;

public class InsertionSort {

	public static void main(String[] args) {
		Random rand = new Random();
		int[] numbers = new int[10];

		for (int i = 0; i < numbers.length; i++) {
			numbers[i] = rand.nextInt(10);
		}

		System.out.println("Before:");
		printArray(numbers);

		insertionSort(numbers);

		System.out.println("\nAfter:");
		printArray(numbers);
	}

	private static void insertionSort(int[] b) {
        [1,2,3,4,5]
         0 1 2 3 4
		for (int i = 4; i < b.length; i++) {
			
			int a=b[i];
            int j=i-1;
            while(j>=0 && b[j]>a){
                b[j+1]=b[j];
                j--;
            }
            b[j+1]=a;
	}
    }
	private static void printArray(int[] numbers) {
		for (int i = 0; i < numbers.length; i++) {
			System.out.println(numbers[i]);
		}
	}
}  
EXAMPLE 2: 

import java.util.*;
public class InsertionSort {
    public static void main(String[] args) {
        Scanner sc= new Scanner(System.in);

        System.out.println("enter the size of array");
        int size=sc.nextInt();
        int[] n=new int[size];

        System.out.println("enter the values: ");
        for(int i=0;i<n.length;i++){
            n[i]=sc.nextInt();
        }

        System.out.println("before insertion sort:");
        for(int i=0;i<n.length;i++){
            System.out.print(n[i]+" ");
        }
        System.out.println();

        for(int i=1; i<n.length;i++){
            int a=n[i];
            int j=i-1;
            while(j>=0 && n[j]>a){
                n[j+1]=n[j];
                j--;
            }
            n[j+1]=a;
        }
         System.out.println("after insertion sort:");
        for(int i=0;i<n.length;i++){
            System.out.print(n[i]+" ");
        }
    }
    
}

SELECTION SORT IN JAVA:

EXAMPLE 1:
import java.util.*;
public class SelectionSort {
    public static void main(String[] args) {
        Scanner sc= new Scanner(System.in);

        System.out.println("enter the size of array");
        int size=sc.nextInt();
        int[] n=new int[size];

        System.out.println("enter the values: ");
        for(int i=0;i<n.length;i++){
            n[i]=sc.nextInt();
        }

        System.out.println("before selection sort:");
        for(int i=0;i<n.length;i++){
            System.out.print(n[i]+" ");
        }
        System.out.println();
        int length=n.length;
        
        for(int i=0;i<length-1;i++){
            int min=n[i];
            int indexofmin=i;
            for(int j=i+1;j<length;j++){
                if(n[j]<n[indexofmin]){
                    min=n[j];
                    indexofmin=j;
                }
            }
            int temp = n[i];
            n[i]=n[indexofmin];
            n[indexofmin]=temp;

        }

         System.out.println("after selection sort:");
        for(int i=0;i<n.length;i++){
            System.out.print(n[i]+" ");
        }
    }
    
}
EXAMPLE 2:

import java.util.*;
public class SelectionSort{
    public static void main(String[] args) {
        int[] numbers= new int[10];
        Random rand=new Random();

        for(int i=0; i<numbers.length;i++){
            numbers[i]=rand.nextInt(10);
        }
        System.out.println("random numbers before selection sort: ");
        for(int i=0;i<numbers.length;i++){
            System.out.print(numbers[i]+" ");
        }
        System.out.println();
        System.out.println("random numbers after selection sort: ");
        selectionsort(numbers);
        
        for(int i=0;i<numbers.length;i++){
            System.out.print(numbers[i]+" ");
        }
    }
    private static void selectionsort(int[] num){
        for(int i=0;i<num.length-1;i++){
            int minIndex=i;
            for(int j=i+1;j<num.length;j++){
                if(num[j]<num[minIndex]){
                    minIndex=j;
                }
            }
            int temp=num[i];
            num[i]=num[minIndex];
            num[minIndex]=temp;
        }
    }
}

MERGE SORT IN JAVA:

import java.util.*;

public class MergeSort {
    public static void main(String[] args) {
        Random rand=new Random();
        int[] numbers= new int[6];
        for(int i=0;i<numbers.length;i++){
            numbers[i]=rand.nextInt(50);
        }
        System.out.println("before");
        printArray(numbers);
        mergesort(numbers);
        System.out.println("after");
        printArray(numbers);
    }
    private static void mergesort(int[]inputArray){
        int inputlength=inputArray.length;
        if(inputlength<2){
            return; 
        }
        int midIndex=inputlength/2;
        int[] lefthalf= new int[midIndex];
        int[] righthalf= new int[inputlength-midIndex];
        for(int i=0;i<midIndex;i++){
            lefthalf[i]=inputArray[i];
        }
        for(int i=midIndex;i<inputlength;i++){
            righthalf[i-midIndex]=inputArray[i];
        }
        mergesort(lefthalf);
        mergesort(righthalf);
        merge(inputArray, lefthalf, righthalf);
    }
    private static void printArray(int[] numbers) {
        for(int i=0;i<numbers.length;i++){
            System.out.println(numbers[i]);
        }
    }
    private static void merge(int[]inputArray,int[]lefthalf,int[]righthalf){
        int rightsize=righthalf.length;
        int leftsize=lefthalf.length;
        int i=0,j=0,k=0;
        while (i<leftsize && j<rightsize) {
            if(lefthalf[i]<righthalf[j]){
                inputArray[k]=lefthalf[i];
                i++;
            }
        else{
            inputArray[k]=righthalf[j];
            j++;
        }
            k++;
        }
        while(i<leftsize){
            inputArray[k]=lefthalf[i];
            i++;
            k++;
        }
        while(j<rightsize){
            inputArray[k]=righthalf[j];
            j ++;
            k++;
        }
    }
}
