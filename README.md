1. A máquina virtual Java (JVM) é uma máquina imaginária que emula uma aplicação em uma máquina real. Ela tem como função permitir a portabilidade do código Java; isso ocorre porque todo código Java é compilado para um formato intermediário, o bytecode. Esse formato é então interpretado pela JVM.

2. O JRE (Java Runtime Environment) contém tudo aquilo que um usuário comum precisa para executar uma aplicação Java (JVM e bibliotecas), como o próprio nome diz é o “Ambiente de execução Java”, já o JDK (O Java Development Kit) é composto pelo JRE e um conjunto de ferramentas úteis ao desenvolvedor Java.

3. 
public class Questao3 {
    public static void main(String[] args) {
        System.out.print("Terminei a primeira aula com um programa Java!");
    }
}

4. Foi retornado um erro por não achar o arquivo da classe para ser executado. A mensagem foi a seguinte: "Error: Could not find or load main class Questao3A1".

5. Na hora de executar, houve um erro por não achar o método main, o que impossibilita ao programa saber por onde a execução deve ser iniciada. A mensagem foi a seguinte: "Error: Main method not found in class Questao3A1".

6.
public class Questao6 {
    public void main(String[] args) {
        System.out.println("Débora Camilly e Caio Pinheiro");
        System.out.println("Flamengo");
    } 
}

7. 
PUBLIC CLASS QUESTAO6A1 {
    PUBLIC STATIC VOID MAIN(STRING[] ARGS) {
        SYSTEM.OUT.PRINTLN("DÉBORA CAMILLY E CAIO PINHEIRO");
        SYSTEM.OUT.PRINTLN("FLAMENGO");
    }
}
O código após ser colocado em letras maiúsculas não pôde mais ser compilado por erros de sintaxe e, consequentemente, também não pôde ser executado.

8. 
Já no momento de compilação, a IDE reclama da diferença do nome e diz que a classe deve estar em um arquivo de nome igual ao seu, caso contrário não haverá nenhum processamento de código.