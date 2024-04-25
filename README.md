# random-1-60
give a randomly number between 1 to 60

import java.util.Random;

public class RandomNumberGenerator {
    public static void main(String[] args) {
        // Rastgele sayı üretmek için Random sınıfını kullanalım
        Random random = new Random();

        // 1 ile 60 arasında rastgele bir sayı seçelim
        int min = 1;
        int max = 60;
        int randomNumber = random.nextInt(max - min + 1) + min;

        System.out.println("Rastgele seçilen sayı: " + randomNumber);
    }
}
