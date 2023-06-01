# Tonos
Examen unidad 6 y 7, Ciencias de datos
import java.util.ArrayList;
import java.util.Collections;

public class Tonos {
    public static void main (String[] args) {
        
        //20 elementos tipo String
        ArrayList<String> tonos= new ArrayList<>();
        tonos.add("Rosa");
        tonos.add("Rubor");
        tonos.add("Salmón");
        tonos.add("Palisandro");
        tonos.add("Maiot");
        tonos.add("Rosado");
        tonos.add("Sandía");
        tonos.add("Coral");
        tonos.add("Limonada");
        tonos.add("Crepa");
        tonos.add("Fucsia");
        tonos.add("Flameco");
        tonos.add("Melocotón");
        tonos.add("Caramelo");
        tonos.add("Magenta");
        tonos.add("Ponche");
        tonos.add("Colorete");
        tonos.add("RosaMexicano");
        tonos.add("Chicle");
        tonos.add("Fresa");

        //Primer elemento de la lista
        System.out.println("El primer tono de rosa es: " + tonos.get(0));
        
        //Ultimo elemento de la lista
        System.out.println("El último tono de rosa es: " + tonos.get(tonos.size() - 1));
        
        // Remove
        tonos.remove(0);
        System.out.println("Lista de tonos despues de eliminar un elemento: " + tonos);
        
        // Add
        tonos.add("Palo");
        
        //Desplegar nuevamente el primer elemento
        System.out.println("El primer tono de rosa es: " + tonos.get(0));
        
        //Buscar el quitno elemento de la lista
        System.out.println("El quinto tono de rosa es: " + tonos.get(4));
        
         // Reverse, invertir los elementos e imprimir la lista 
        Collections.reverse(tonos);
        System.out.println("Tonos invertidos: " + tonos);
        
    }
}
