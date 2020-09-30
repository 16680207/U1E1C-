/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package U1E3;
import java.util.*;
/**
 *
 * @author Uziel
 */
public class U1E3 {

    /**
     * @param args the command line arguments
     */
 
     public static void main(String[] args) {
       // Valores que tiene el array A desordenado.
        Scanner tecla = new Scanner(System.in);
        Scanner key = new Scanner(System.in);
        int tam;
        System.out.println("Ingrese # PALABRAS");
        tam = tecla.nextInt();
        String[] A= new String[tam]; 
        for(int i=0; i<A.length; i++) 
        {
            System.out.println("Ingrese TEXTO: "+i);
            A[i] = key.nextLine();
        }
       
        // Imprimimos la frase desordenada 
        System.out.println("Frase desordenada : "); 
        for(int i=0; i<A.length; i++) 
        {System.out.println( " A[" + i + "] = " + A[i] ); }
       
        // Inicio del metodo de ordenamiento de la Burbuja
        String aux; 
        for(int i=1; i<=A.length; i++) {  
            for(int j=0; j<A.length-i; j++) { 
                if( A[j].compareTo( A[j+1] ) > 0 ) { 
                    aux   = A[j]; 
                    A[j]  = A[j+1]; 
                    A[j+1]= aux; 
                }    
            } 
        }}}
