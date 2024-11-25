public class Main {

    public static void main(String[] args) {
        int rows = 5;
        int cols = 4;

        // Declare and initialize the 2D array
        int[][] array = new int[rows][cols];

        // Populate the array using nested loops
        for (int i = 0; i < rows; i++) {
            for (int j = 0; j < cols; j++) {
                array[i][j] = i * j;
            }
        }

        // Print the array
        for (int i = 0; i < rows; i++) {
            for (int j = 0; j < cols; j++) {
                System.out.print(array[i][j] + " ");
            }
            System.out.println();
        }
    }
}
