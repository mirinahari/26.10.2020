package com.company;


import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        String id = "123456";
        String full_name = "miri nahari";
        String address = "hasivim 6";
        String details = (id + (" ") + full_name +(" ") + address);

        Scanner scanner = new Scanner(System.in);
        //String full_name = "miri nahari";
        String fname = scanner.nextLine();
        String lname = scanner.nextLine();

        String details2 = (fname + (" ") + lname);

        System.out.print(details2);

    }
}



