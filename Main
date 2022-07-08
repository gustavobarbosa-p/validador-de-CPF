import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner tec = new Scanner(System.in);

        String cpf = tec.next();

        char d1 = cpf.charAt(0);
        int i1 = Character.getNumericValue(d1);

        char d2 = cpf.charAt(1);
        int i2 = Character.getNumericValue(d2);

        char d3 = cpf.charAt(2);
        int i3 = Character.getNumericValue(d3);

        char d4 = cpf.charAt(4);
        int i4 = Character.getNumericValue(d4);

        char d5 = cpf.charAt(5);
        int i5 = Character.getNumericValue(d5);

        char d6 = cpf.charAt(6);
        int i6 = Character.getNumericValue(d6);

        char d7 = cpf.charAt(8);
        int i7 = Character.getNumericValue(d7);

        char d8 = cpf.charAt(9);
        int i8 = Character.getNumericValue(d8);

        char d9 = cpf.charAt(10);
        int i9 = Character.getNumericValue(d9);

        char d10 = cpf.charAt(12);
        int i10 = Character.getNumericValue(d10);

        char d11 = cpf.charAt(13);
        int i11 = Character.getNumericValue(d11);

        int validacao1 = (i1 * 10) + (i2 * 9) + (i3 * 8) + (i4 * 7) + (i5 * 6) + (i6 * 5) + (i7 * 4) + (i8 * 3) + (i9 * 2);
        int resto1 = validacao1 * 10;
        
        int validacao2 = (i1 * 11) + (i2 * 10) + (i3 * 9) + (i4 * 8) + (i5 * 7) + (i6 * 6) + (i7 * 5) + (i8 * 4) + (i9 * 3) + (i10 * 2);
        int resto2 = validacao2 * 10;

        int pts = 0;

        if(resto1 % 11 == i10) {
            pts+=1;
        }if(resto2 % 11 == i11) {
            pts+=1;
        }

        if(pts == 2) {
            System.out.println("VALIDO");
        }else {
            System.out.println("INVALIDO!");
        }
    }
}
