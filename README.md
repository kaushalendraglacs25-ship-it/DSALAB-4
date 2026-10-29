# DSALAB-4
// //----------------------PREFIX SUM------
// import java.util.Arrays;
// import java.util.Scanner;
// public class lab4 {
// public static void main(String args[]){
//     Scanner sc = new Scanner(System.in);
//     int n= sc.nextInt();
//     int arr[]=new int[n];
//     for(int i=0;i<arr.length;i++){
//     arr[i]=sc.nextInt();
//     }
//     for(int i=1;i<arr.length;i++){
//     arr[i]=arr[i]+arr[i-1];
//     }
//     //for(int i=0;i<arr.length;i++){
//     System.out.println(Arrays.toString(arr));
//     //}
//    sc.close(); }
// }
//-----------------------FREQUENCY COUNT---------------
//10,20,10,30,10,40
// import java.util.Arrays;
// import java.util.Scanner;
// class lab4{
//     public static void main(String args[]){
//         Scanner sc = new Scanner(System.in);
//         int n= sc.nextInt();
//         int count=0;
//         int arr[]=new int[n];
//         for(int i=0;i<arr.length;i++){
//             arr[i]=sc.nextInt();
//         }
//         Arrays.sort(arr);
//         for(int i=1;i<arr.length;i++){
//             if(arr[i]==arr[i-1])
//                 count++;
//         }
//         System.out.println(count);
//         sc.close();
//     }
// }

//COUNT EVEN AND ODD NUMBERS:----
// import java.util.Scanner;
// class lab4{
//     public static void main(String args[]){
//         Scanner sc = new Scanner(System.in);
//         System.out.println("ENTER SIZE OF ARRAY:");
//         int n= sc.nextInt();
//         int arr[]=new int[n];
//         int Evencount=0;
//         int Oddcount=0;
//         for(int i=0;i<arr.length;i++){
//         System.out.println("ENTER ELEMENT IN ARRAY:");
//         arr[i]=sc.nextInt();}
//  for(int i=0;i<arr.length;i++){
// if(arr[i]%2==0){
//     Evencount++;
// }
//  else{
//     Oddcount++;}
// }
// System.out.println("Even numbers: " + Evencount);
// System.out.println("Odd numbers: " + Oddcount); 
//     sc.close();}
// } 

//-----------------REMOVE ZEROS-------
// import java.util.Scanner;
// class lab4{
//     public static void main(String args[]){
//         Scanner sc = new Scanner(System.in);
//         int n=sc.nextInt();
//         int arr[]=new int[n];
//         int arr1[]=new int[n];
//     for(int i=0;i<arr.length;i++){
//         arr[i]=sc.nextInt();
//     }
//     int j=0;
// for(int i=0;i<arr.length;i++){
//     if(arr[i]!=0){
//     arr1[j]=arr[i];
//     j++;}
// }
// for(int i=0;i<j;i++){
// System.out.println(arr1[i]+" ");}
//     sc.close();
//     }}
