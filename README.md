# Task-JavaNestedIfElse
import java.util.Scanner;

public class TaskNestedIf {

    public static void main(String[] args) {
        Scanner inputusia = new Scanner(System.in);
        System.out.println("Masukkan usia pembaca" );
        int usia = inputusia.nextInt();
        if (usia <= 12) {
            System.out.println("Anak-anak");
            System.out.println("Rekomendasi buku cerita");
        } else if (usia >= 13 && usia <= 17) {
            System.out.println("Remaja");
            System.out.println("Rekomendasi buku petualang");
        } else {
            System.out.println("Dewasa");
            System.out.println("Rekomendasi buku non-fiksi");  
        }    
    }
}
