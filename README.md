# DSA-Practice

//Program to find largest element in an Array

public class Main
{
	public static void main(String[] args) {
		int []arr = {6,3,4,5,8};
		int max = arr[0];
		
		for(int i=1; i< arr.length;i++){
		    if(arr[i] > max){
		        max = arr[i];
		    }
		}
		System.out.println(max);
	}
}
