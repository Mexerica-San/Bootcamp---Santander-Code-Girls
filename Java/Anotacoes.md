# Sobre o funcionamento JAVA:  
### Bytecode  
 *Bytecode* é um formato de código intermediário entre o código fonte, o texto que o programador consegue manipular, e o código de máquina, que o computador consegue executar. Na plataforma Java, o *bytecode* é interpretado por uma máquina virtual Java (JVM). A portabilidade do código Java é obtida à medida que máquinas virtuais Java estão disponíveis para diferentes plataformas. Assim, o código Java que foi compilado em uma máquina pode ser executado em qualquer máquina virtual Java, independentemente de qual seja o sistema operacional ou o processador que executa o código:  
[Fonte](https://www.dca.fee.unicamp.br/cursos/PooJava/javaenv/bytecode.html) 
![Processo JAVA](https://www.dca.fee.unicamp.br/cursos/PooJava/javaenv/java_mec.gif) 
### Processo Java  
 - Código fonte: código desenvolvido pelo programador  
 - JDK: (Java Development Kit) é o Kit de Desenvolvimento Java responsável por compilar código-fonte (.java) em bytecode (.class)  
 - JVM: (Java Virtual Machine) é a Máquina Virtual do Java reponsável por executar o bytecode (.class)  
 - JRE: (Java Runtime Environment) é o Ambiente de Execução do Java que fornece as bibliotecas padrões do Java para o JDK compilar o seu código e para a JVM executar o seu programa.  
  #### Fluxo   
  1) Você escreve o seu código-fonte (arquivo com a extensão .java). 
  2) Você utiliza o JDK para compilar o seu código-fonte e gerar o arquivo bytecode (arquivo com a extensão .class). 
  3) Para executar o seu programa, a JVM lê o seu arquivo compilado (.class) e as bibliotecas padrões do Java que estão no JRE.  
  4) Pronto, seu programa está rodando.  
 [Fonte](http://www.mauda.com.br/?p=805)  
 [Fonte](https://dicasdejava.com.br/qual-a-diferenca-entre-jdk-jre-e-jvm/)
 ![Etapas de tradução para programa Java](http://videos.web-03.net/artigos/Higor_Medeiros/Execucao_Programas_Java/Execucao_Programas_Java1.jpg)
 ![Arquitetura Geral da linguagem Java](https://lh3.googleusercontent.com/-Jt7Ul-mEQac/Vjv3JFXTmGI/AAAAAAAAAQo/jAoHdtCIqN0/s1024-Ic42/ArquiteturaJava-Macro.png)



 
