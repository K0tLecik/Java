package com.company;
import java.util.Random;
import java.util.Scanner;

//Zadanie 1

//public class Main {
//    public static void main(String[] args) {
//        int n;
//        Scanner scan = new Scanner(System.in);
//        System.out.print("Wpisz n:");
//        n = scan.nextInt();
//        int tab[] = new int[n];
//            for(int i = 0;i < n;i++){
//            System.out.print("Wpisz "+(i+1)+" liczbę: ");
//            tab[i] = scan.nextInt();
//        }
//        showPrimes(tab);
//    }
//    public static void showPrimes(int[] list){
//        int suma = 0;
//        for(int i = 0; i < list.length;i++){
//            for(int x = 1;x<=list[i];x++) {
//                if(list[i] % x == 0)suma++;
//            }
//            if(list[i] == 1) System.out.print(list[i]);
//            if(suma == 2) System.out.print(list[i]);
//            suma = 0;
//        }
//    }
//}

//Zadanie 2

//public class Main {
////    public static void main(String[] args) {
////        Scanner scan = new Scanner(System.in);
////        int n = 0;
////        n = scan.nextInt();
////        najwieksza(n);
////    }
////
////    public static void najwieksza(int n) {
////        Random r = new Random();
////        int najw = 50 - r.nextInt(100);
////        int tab[] = new int[n - 1];
////        int wys = 1;
////        for(int i =1;i < n - 1;i++){
////            tab[i] = 50 - r.nextInt(100);
////            if(tab[i] == najw)wys++;
////            if(tab[i] > najw){
////                najw=tab[i];
////                wys=1;
////            }
////        }
////        System.out.print("Największa liczba to :"+najw+" i występuje "+wys+" razy");
////    }
////}


//Zadanie 2

//public class Main {
////    public static void main(String[] args) {
////        Scanner scan = new Scanner(System.in);
////        int n = 0;
////        n = scan.nextInt();
////        najwieksza(n);
////    }
////
////    public static void najwieksza(int n) {
////        Random r = new Random();
////        int najw = 50 - r.nextInt(100);
////        int tab[] = new int[n - 1];
////        int wys = 1;
////        for(int i =1;i < n - 1;i++){
////            tab[i] = 50 - r.nextInt(100);
////            if(tab[i] == najw)wys++;
////            if(tab[i] > najw){
////                najw=tab[i];
////                wys=1;
////            }
////        }
////        System.out.print("Największa liczba to :"+najw+" i występuje "+wys+" razy");
////    }
////}

//Zadanie 3

public class Main {
    public static void main(String[] args) {
        String str = "abcabcabcabc";
        char c = 'c';
        System.out.print(delete(str,c));
    }

    public static String delete(String str,char c){
        int wys = 0;
        for(int i = 0;i < str.length();i++){
            if(str.charAt(i) == c){
                if(wys>0) str.charAt(i) = '';
                wys++;
            }
        }
        return str;
    }
}
