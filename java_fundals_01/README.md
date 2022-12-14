# 1. Hello World Java

# Nosso primeiro programa em Java: imprimindo uma linha de texto.

<p>
Vamos criar o nosso primeiro programa utilizando a linguagem de programação Java, mas antes ...
Vamos verificar a instalação do Java realizada no computador, lembre-se, eu estou utilizando o Sistema Operacional Windows neste tutorial, em outros sistemas a forma de operacionalização é um pouco diferente, no futuro atualizarei o tutorial com manipulações no Sistema Operacional Linux.
</p>
<p>
<ol>
  <li>Clique no botão iniciar do Windows, na caixa de pesquisa digite: <em>cmd</em> e pressione "ENTER". O prompt de comando será inicializado.</li>
  <li>No prompt de comando digite: <em>java -version</em></li>
</ol>
</p>

> Observe que o terminal retorna uma resposta, informando a versão do Java instalado no Sistema Operacional do computador. Se o terminal retornar alguma mensagem de não reconhecimento do Java, possívelmente o Java não foi instalado no seu computador. Retorne para seção de introdução, para o tutorial indicado sobre a instalação e configuração do Java.
> Também é informado a versão do Java instalado, no caso, no momento da construção deste tutorial, a versão utilizada é a 18.0.1.1. Se sua versão for maior ou igual a 8.0.0.0, está tudo bem, você pode seguir em frente neste treinamento, caso contrário você deve retornar ao tutorial de instalação do Java e atualizá-lo.

<br />

![Prompt de Comando](../imgs/f_01_prompt_de_comando.png)

<p>
  <ol start="3">
    <li>Após confirmação da instalação do  Java, ainda no prompt de comando para acessar a raiz do disco (C:\), digite: <em>cd \</em></li>
    <li>Em seguida, para criar um diretório, digite: <em>mkdir scripts_java</em> e pressione "ENTER";</li>
    <li>Digite <em>cd scripts_ java</em> para acessar o diretório criado.</li>
  </ol>
</p>

![Prompt de Comando](../imgs/f_01_create_folder.png)

<p>
  <ol start="6">
    <li>Carregue o programa bloco de notas</li>
    <li>Digite o script abaixo:</li>
  </ol>
</p>

```java
public class App {
	public static void main(String[] args) {
		System.out.println("Hello World Java!!!");
	}
}
```

<p>
  <ol start="8">
    <li>Salve na pasta "scripts_java" criada na unidade (C:\) com o nome "App.java";</li>
    <li>Retorne para o terminal e digite o comando: <em>javac App.java</em>;</li>
    <li>Em seguida, digite o comando: <em>java App</em>.</li>
  </ol>
</p>

![Prompt de Comando](../imgs/f_01_executa_java.png)

> Observe que o script do arquivo App.java é compilado para App.class e após execução do comando <em>java App</em> o script é executado, retonando "Hello World Java!!!". Nas próximas seções aprenderemos sobre cada comando digitado no código-fonte App.java.

<br />

**criamos um programa que imprime uma mensagem na tela.**
