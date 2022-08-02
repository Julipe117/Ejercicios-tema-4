# Ejercicios-tema-4
Ejercicios del tema 4 de OpenBootCamp

//Ejercicio If-Else

class IfElse {
    public static void main (String[] args) {
        int numeroIf = -1;
        if (numeroIf > 0)
            System.out.println("Positivo");
         else if (numeroIf == 0)
            System.out.println("0");
         else
            System.out.println("Negativo");
    }
}

//Ejercicio While

class While{   
    public static void main (String[] args){
        int numeroWhile = 0;
        while (numeroWhile < 3){
            System.out.println(numeroWhile);
            numeroWhile ++;
        }
    }
}

//Ejercicio Do While

class DoWhile{
    public static void main (String[] args){
        int numeroWhile = 3;
        do{
        System.out.println(numeroWhile);
        numeroWhile ++;
        } while (numeroWhile < 3);
    }
}


//Ejercicio For

class For{
    public static void main (String[] args){
        for (int numeroFor = 0; numeroFor <= 3; numeroFor ++){
        System.out.println(numeroFor);
        }
    }
}

//Ejercicio Switch

class Switch{
    public static void main(String[] args){
        int estacion = 5;
        switch (estacion) {
            case 6: case 7: case 8:
                System.out.println("Verano");
                break;
            case 9: case 10: case 11:  
                System.out.println("Otoño");
                break;
            case 12: case 1: case 2:
                System.out.println("Invierno");
                break;      
            case 3: case 4: case 5:
                System.out.println("Primavera");
                break;  
            default:
                System.out.println("No es una estacion del año");
        }
    }
}
