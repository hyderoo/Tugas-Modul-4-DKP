package com.example.Modul4;
import java.util.Scanner;

public class Tugas {
    public static void daftarVaksin(){
        System.out.println("Vaksin Primer: ");
        System.out.println("1. Sinovac");
        System.out.println("2. AstraZeneca");
        System.out.println("3. Pfizer");
        System.out.println("4. Moderna");
        System.out.println("5. Janssen");
        System.out.println("6. Sinopharm");
        System.out.println("7. Batalkan program");
    }
    public static String selesai(String text){
        return text;
    }
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        Booster vaksin = new Booster();
        System.out.println("======Program Penentuan Doksis Vaksin Booster======");

        while (true){
            daftarVaksin();
            System.out.print("Masukan Vaksin Primer Anda: ");
            int i = sc.nextInt();
            System.out.println("===================================================");
            if(i == 1){
                System.out.println("Vaksin primer anda adalah Sinovac");
                vaksin.sinovac();
                System.out.println("===================================================");
            }
            else if(i == 2){
                System.out.println("Vaksin primer anda adalah AstraZeneca");
                vaksin.astraZeneca();
                System.out.println("===================================================");
            }
            else if(i == 3){
                System.out.println("Vaksin primer anda adalah Pfizer");
                vaksin.pfizer();
                System.out.println("===================================================");
            }
            else if(i == 4){
                System.out.println("Vaksin primer anda adalah Moderna");
                System.out.println(vaksin.moderna());
                System.out.println("===================================================");
            }
            else if(i == 5){
                System.out.println("Vaksin primer anda adalah Janssen");
                System.out.println(vaksin.janssen());
                System.out.println("===================================================");
            }
            else if(i == 6){
                System.out.println("Vaksin primer anda adalah Sinopharm");
                String sino = vaksin.sinopharm("Dosis Vaksin Booster adalah 1 Dosis Sinopharm");
                System.out.println(sino);
                System.out.println("===================================================");
            }
            else{
                System.out.println(selesai("Program dibatalkan"));
                System.out.println((selesai("Terima kasih telah menggunakan program ini:)")));
                System.out.println("===================================================");
                break;
            }

        }

    }
}
