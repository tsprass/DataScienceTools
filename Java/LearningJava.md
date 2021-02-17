Tutorial de Java
================
Taiane S. Prass

<div style="float:right; padding:100px">

<p style="float: left;">
<img src="logojava.jpg" width="100" />
</p>

Este é um tutorial de Java voltado para iniciantes. Nele vamos discutir
conceitos básicos relacionados à programação em Java.

<p></p>

O tutorial é baseado no vídeo [Java Programming All-in-One Tutorial
Series (6 HOURS!)](<https://www.youtube.com/watch?reload=9&v=r3GGV2TG_vw>)

</div>

# Motivação

Java é uma linguagem de programação orientada a objetos desenvolvida na
década de 90. Atualmente, é uma das linguagem de programação mais
populares. Uma das grandes vantagens do Java em relação a outras
linguagens de programação modernas é o fato da linguagem Java ser
compilada para um *bytecode* que é interpretado por uma máquina virtual
(*Java Virtual Machine* - JVM). Dessa forma, aplicativos escritos nessa
linguagem podem rodar em diferentes plataformas (Windows, MAC, Linux)
com pouco trabalho.

## Arquitetura do Java

<div style="float:right; padding:1px">

<p style="float: left;">
<img src="arquitetura.png" width="600" />
</p>

Escrevemos um código, isto é, uma série de comandos que dizem ao
computador o que fazer. Esse código (*source code*) é salvo em um
arquivo com extensão “.java”.

O código é então compilado em algo conhecido como *bytecode*. O arquivo
gerado nessa etapa terá a extensão “.class”

O *bytecode* pode ser executado em qualquer sistema operacional:
Windows, MAC, Linux.

</div>

## Qual é a mágica por trás disso?

O JDK (*Java Development Kit*), é um conjunto de ferramentas para
programação em java. O JRE (*Java Runtime Environment*) é um conjunto de
componentes para criar e executar aplicações Java. Os componentes do JRE
incluem a máquina virtual Java (JVM), bibliotecas de classe Java e o
carregador de classes Java.

Os JDKs são usados para desenvolver softwares Java, os JREs oferecem
ferramentas de programação e tecnologias de implantação, e as JVMs
executam programas nessa linguagem.

**Observação:** As constantes atualizações do Java em seu computador
servem para atualizar o JRE.

Download:

-   JDK:
    <https://www.oracle.com/java/technologies/javase-downloads.html>

-   JRE: <https://www.java.com/pt-BR/download/>

# Primeiro Programa em Java

Faça o download do JDK e instale conforme as instruções.

Precisaremos também de um IDE (*Integrated Development Environment* ou
Ambiente de Desenvolvimento Integrado) que é um programa de computador
que reúne características e ferramentas de apoio ao desenvolvimento de
software com o objetivo de agilizar este processo. Os IDE mais
utilizados são **eclipse** (<https://www.eclipse.org/ide/>) e
**netbeans** (<https://netbeans.org/>). Para esse tutorial vamos
utilizar o eclipse.

O próximo passo é criar um novo projeto:

<div style="float:center; padding:1px">

<img src="p1.png" width="600" />

</div>

**Observação:** Caso apareça uma mensagem de erro do tipo (aconteceu
comigo)

> *The project was not built due to “Failed to init ct.sym for
> C:\\Users\\…\\jrt-fs.jar” Fix the problem, then try refreshing this
> project and building it since it may be inconsistent* &gt;

veja as sugestões nessa página:
<https://stackoverflow.com/questions/63446925/the-project-was-not-built-due-to-failed-to-init-ct-sym-for-c-program-files-jav>
