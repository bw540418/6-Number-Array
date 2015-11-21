# Sorting an Array
Our goal for this project was to take 6 number and sort them using Arrays and custom Methods

## Java Code
```java

public class Array_sorting {

	public static void main(String[] args) {
		
		//System.out.println("this is my test statement");
		
		//call the array test method
		ArraySortingMethod();
	}

			public static void ArraySortingMethod(){
				System.out.println("Index\tValue");
				
				int Array[]={32,12,18,54,2,17};
				
				for(int counter=0;counter<Array.length;counter++){
					for(int j=0;j<Array.length;j++){
						if(Array[counter]<Array[j]){
							int temp;
							temp=Array[counter];
							Array[counter]=Array[j];
							Array[j]=temp;
						}
					}
				}
				for(int counter=0;counter<Array.length;counter++)
					System.out.println("Array["+counter+"]="+ Array[counter]);
}
}

```

## Console Output
```
Index	Value
Array [0]=2
Array [1]=12
Array [2]=17
Array [3]=18
Array [4]=32
Array [5]=54
```

## Command Prompt Output
```
Microsoft Windows [Version 6.3.9600]
(c) 2013 Microsoft Corporation. All rights reserved.

C:\Users\Brinden Wallace>cd workspace

C:\Users\Brinden Wallace\workspace>cd "Array Sorting"

C:\Users\Brinden Wallace\workspace\Array Sorting>echo # ArraySorting >> README.md

C:\Users\Brinden Wallace\workspace\Array Sorting>git init
'git' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\Brinden Wallace\workspace\Array Sorting>
```

## Conclusion
In this project I still had trouble with git hub on my home computer and still need to talk to you about how I can get git hub working at home. but other than that it was interesting figuring out how to make my array sort and work itself. I found out you can replace the "i" in your for loops with "counter". Im not sure if you can use any name for the variable but I know counter works in place of i as of right now.
