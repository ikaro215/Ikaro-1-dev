
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner entrada = new Scanner(System.in);

        double salario, porcentagem, novoSalario;

        System.out.print("Digite o salario atual: R$ ");
        salario = entrada.nextDouble();

        System.out.print("Digite a porcentagem do aumento: ");
        porcentagem = entrada.nextDouble();

        novoSalario = salario + (salario * porcentagem / 100);

        System.out.printf("Novo salario: R$ %.2f%n", novoSalario);

        entrada.close();
    }
}
