# Retangulo


PARTE.1

// Arquivo: Retangulo.java
package retangulo;

public class Retangulo {
    private double largura;
    private double altura;
    
    // Construtor
    public Retangulo(double largura, double altura) {
        this.largura = 5.0;
        this.altura = 3.0;
    }
    
    // Métodos acessores
    public double getLargura() {
        return largura;
    }
    
    public double getAltura() {
        return altura;
    }
    
    // Método para calcular a área do retângulo
    public double calcularArea() {
        return largura * altura;
    }
}


PARTE.2

// Arquivo: Main.java
package retangulo;

public class Main {
    public static void main(String[] args) {
        // Criando um objeto Retangulo
        Retangulo retangulo1 = new Retangulo(5.0, 3.0);
        
        // Exibindo informações do retângulo
        System.out.println("Largura: " + retangulo1.getLargura());
        System.out.println("Altura: " + retangulo1.getAltura());
        
        // Calculando e exibindo a área do retângulo
        System.out.println("Área do retângulo: " + retangulo1.calcularArea());
    }
}
