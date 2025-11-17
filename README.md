import java.util.ArrayList;

public class tempCodeRunnerFile {
    public static void main(String[] args) {

        // ---- ARRAY EXAMPLE ----
        // Fixed size array of integers
        int[] numbersArray = new int[5];
        numbersArray[0] = 10;
        numbersArray[1] = 20;
        numbersArray[2] = 30;
        numbersArray[3] = 40;
        numbersArray[4] = 50;

        System.out.println("Array Elements:");
        for (int i = 0; i < numbersArray.length; i++) {
            System.out.println("Index " + i + ": " + numbersArray[i]);
        }

        // ---- ARRAYLIST EXAMPLE ----
        // Dynamic ArrayList of integers
        ArrayList<Integer> numbersList = new ArrayList<>();
        numbersList.add(10);
        numbersList.add(20);
        numbersList.add(30);
        numbersList.add(40);
        numbersList.add(50);

        // Adding a new element dynamically
        numbersList.add(60);

        System.out.println("\nArrayList Elements:");
        for (int i = 0; i < numbersList.size(); i++) {
            System.out.println("Index " + i + ": " + numbersList.get(i));
        }

        // Removing an element from ArrayList
        numbersList.remove(2); // removes the third element (30)

        System.out.println("\nArrayList after removing index 2:");
        System.out.println(numbersList);
    }
}
