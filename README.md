# javaprogram
import java.util.*;
class Main{
    public static int LargestElement(){
    int arr[] = {5,7,1,2,9};
    int max = arr[0];
    for(int i=0;i<arr.length;i++){
        if(max<arr[i])
        {
            max  = arr[i];
        }
    }
    return max;
}
    public static void main(String[] args){
        System.out.print("Largest element is: "+LargestElement());
    } 
}
