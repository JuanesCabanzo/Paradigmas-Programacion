public class Ordenamiento {

    public static void main(String[] args) {

        int[] numeros = {8, 3, 5, 1, 9, 2, 7};

        System.out.println("Números antes de ordenar:");

        for (int numero : numeros) {
            System.out.print(numero + " ");
        }

        // Orden usando el método burbuja
        for (int i = 0; i < numeros.length - 1; i++) {

            for (int j = 0; j < numeros.length - 1 - i; j++) {

                if (numeros[j] > numeros[j + 1]) {

                    int temporal = numeros[j];
                    numeros[j] = numeros[j + 1];
                    numeros[j + 1] = temporal;
                }
            }
        }

        System.out.println("\n\nNúmeros después de ordenar:");

        for (int numero : numeros) {
            System.out.print(numero + " ");
        }
    }
}
