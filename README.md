# Retangulo


PARTE.1
package retangulo;

public class Retangulo {
    public static void main(String[] args) {
        // Criando um objeto Retangulo
        Retangulo2 retangulo1 = new Retangulo2(5.0, 3.0);
        
        // Exibindo informações do retângulo
        System.out.println("Largura: " + retangulo1.getlargura());
        System.out.println("Altura: " + retangulo1.getaltura());
        
        // Calculando e exibindo a área do retângulo
        System.out.println("Área do retângulo: " + retangulo1.calcularArea());
    }
}

PARTE.2

//Classe Retangulo:
//Crie uma classe Retangulo com os atributos largura e altura.
//Implemente um método construtor que inicialize esses atributos.
//Em seguida, crie métodos acessores para os atributos largura e altura,
//e um método para calcular a área do retângulo.
package retangulo;

public class Retangulo2 {

    //variaveis
    private double largura;
    private double altura;

    // Construtor
    public Retangulo2(double largura, double altura) {
        this.largura = 5.0;
        this.altura = 3.0;
    }

    //metodo setLargura
    public double setlargura(double largura) {
        this.largura = largura;
        return largura;

    }

    // Métodos acessores
    public double getlargura() {
        return largura;
    }

    //metodo setAltura
    public double setaltura(double altura) {
        this.altura = altura;
        return altura;
    }

    public double getaltura() {
        return altura;
    }

    // Método para calcular a área do retângulo
    public double calcularArea() {
        return largura * altura;
    }
}



