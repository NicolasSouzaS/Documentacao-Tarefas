# Documentação de atividade
> ## Principio/Objetivo
* Data 08/05/2023 recebemos o trabalho de criar uma aplicação utilizando diversas ferramentas tais com o objetivo voltado para uma aplicação de inserção a um banco de dados e por fim transformar a aplicação em um container, recorremos a linguagem de programação, um editor de código, gerenciador de banco de dados, um gerenciador de dependencias, ferramenta de teste, containers e por fim automatizar o processo.
#
> ## Ferramentas utilizadas para a aplicação:
[![Ferramentas utilizadas](https://skillicons.dev/icons?i=java,maven,eclipse,spring,jenkins,github,docker,postman,)](#)

> ## Linguagem de programação:Java (SE - 17)
[![Linguagem de programação Java](https://skillicons.dev/icons?i=java)](https://www.javatpoint.com/java-tutorial)


 ## O que é Java ? Historia Java

* Java é uma linguagem de programação orientada a objetos de alto nível, criada em 1995 pela Sun Microsystems (adquirida posteriormente pela Oracle Corporation). 

* A linguagem Java é fortemente tipada, o que significa que cada variável deve ser declarada com seu tipo antes de ser usada. Ela também suporta o conceito de herança, polimorfismo, encapsulamento e abstração, que são fundamentais na programação orientada a objetos.
#
## Utilização da linguagem dentro da aplicação

* Utilizamos a lingugagem Java para a parte de back-end dentro da aplicação web, dentro da mesma utilizamos um editor de código Eclipse, em meio de código realizamos a ação de criar tabela dentro de um banco de dados (MySQL), utilizamos a função de criar ações como cadastrar tuplas(linhas) dentro do banco de dados e em seguida realizamos a ação de listar tais informações cadastradas.

* Utilizando a mesma criamos diversas classes e interfaces para a ajuda de ações dentro do sistema, criamos classes voltadas para o objetivo de serem Controllers, Domains e Repositorys, classes setadas com essas funções vem junto da ajuda de uma outra ferramenta chamada "Spring Boot" a mesma ajuda a velocidade de criação de uma aplicação web.
#
## Para mais informações sobre a linguagem
* Documentação sobre a linguagem e métodos de uso

[![Linguagem de programação Java](https://skillicons.dev/icons?i=java)](https://www.javatpoint.com/java-tutorial)
#
> ## Editor de código Eclipse
[![Editor de código Ecplise](https://skillicons.dev/icons?i=eclipse)](https://www.eclipse.org/documentation/)

## O que é editor de código ?
* Um editor de código é um programa de computador utilizado para escrever e editar código-fonte de programas. Ele permite que os programadores escrevam e editem o código-fonte com recursos que ajudam a detectar erros e facilitam a navegação e edição do código.

* Os editores de código podem variar desde editores de texto simples até ferramentas mais avançadas que oferecem recursos avançados de desenvolvimento, como realce de sintaxe, auto completar de código, indentação automática, depuração de código, integração com controle de versão, e assim por diante.
#
## Editor de código Eclipse:
* O Eclipse é um ambiente de desenvolvimento integrado (IDE) de código aberto amplamente utilizado para desenvolvimento de software em diversas linguagens, como Java, C++, Python, PHP, entre outras. O Eclipse é muito popular entre desenvolvedores Java e é conhecido por sua grande variedade de recursos e plugins.

* Utilizamos o editor de código IDE Eclipse para desenvolver com maior performace a linguagem de desenvolvimento de aplicação Java, criamos e utilizamos diversas classes e interfaces, o editor de código nos disponibiliza diversas possibilidades como criação de packeges(pacotes) e integração dos mesmos com a implementação com gerenciadores de banco de dados.
#
## Utilização da ferramenta:
* A utilização da ferramenta se dedicou e teve como objetivo principal o auxilio de digitação e suporte para o desenvolvimento melhor até o final da aplicação. Resumidamente a funcionalidade da ferramenta se destaca para uma edição de código que te guia de melhor forma para o objetivo.
#
> ## Para mais informações sobre Eclipse
 - Documentação sobre a ferramenta e utilização
###  [![Editor de código Ecplise](https://skillicons.dev/icons?i=eclipse)](https://www.eclipse.org/documentation/)
#
> ## Framework Spring Boot
[![Framework Spring Boot](https://skillicons.dev/icons?i=spring)](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)

## O que é o Framework Spring ?
*  O Spring Boot é um framework open-source para desenvolvimento de aplicações Java que visa simplificar o processo de criação e configuração de projetos, permitindo que os desenvolvedores foquem na implementação de funcionalidades em vez de gastar tempo com configurações complexas.

* O Spring Boot oferece uma série de funcionalidades prontas para uso, como autoconfiguração, integração com outros frameworks, monitoramento de saúde da aplicação, entre outras. 
#

## Objetivo dado a ferramenta dentro da aplicação:

* Recorremos a essa ferramenta pelo motivo não só de cortar alguns caminhos e economizar tempo, mas também como obtivermos um método de código mais limpo. Como dito antes, o Spring Boot se torna um encurtador do caminho, por exemplo, no meio de nossa atividade temos o trabalho de abrir uma conexão ao banco de dados, inserir dados, ler dados e etcetera.

* O Spring Boot contém diversas bibliotecas que possuem o intuito de fazer essas e outras ações por nós ao invés de temos um trabalho ainda maior de nós mesmos termos que implementar isso a aplicação.

* A forma de criar a conexão com o banco de dados no nosso caso MySQL, a ferramenta em meio a criação do projeto com os drivers que indicamos (MySQL Driver, Spring Boot DevTools, Spring Web, Spring Actuator, Spring JPA), a mesma nos facilita o trabalho criando um arquivo dentro src/main/resources/application.properties, esse arquivo contém a porta de comunicação com o banco, ip do servidor que possui o banco, usuario e senha.

Exemplo:
![Exemplo-application.properties](/imgs/Ex.png) 
Na sublinhagem a esquerda, o caminho de encontro ao arquivo, direita, o método de código de acesso | conexão com o banco.
#
## Para mais informações sobre Spring Boot
 * Documentação informativa a método de uso e informações
[![Documentação Spring Boot](https://skillicons.dev/icons?i=spring)](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)
#
> ## Ferramenta de colaboração Postman 
[![Postman](https://skillicons.dev/icons?i=postman)](https://learning.postman.com/docs/publishing-your-api/documenting-your-api/)

## O que é Postman ?
* Postman é uma ferramenta de colaboração para desenvolvimento de APIs (Interface de Programação de Aplicativos) que permite que os desenvolvedores testem, documentem e compartilhem suas APIs com facilidade.

* Com o Postman, os desenvolvedores podem criar solicitações HTTP personalizadas para testar as APIs, visualizar as respostas em diferentes formatos (como JSON, XML, HTML e outros).
#
## Utilização da ferramenta:
* Como dito no resumo sobre a ferramenta, utilizamos a ferramenta para se tornar um método de teste, assim como antes comentamos sobre o Spring Boot que nos auxilio na criação da conexão com o banco, inserção de dados, leitura de dados e etcetera, o Postman é uma das formas de realizar o teste de inserir e retirar os dados do banco, através do caminho http e porta setada no application.properties.
#
## Para mais desejos de informações
* Documentação sobre a ferramenta em questão

    [![Documentação sobre o Postman](https://skillicons.dev/icons?i=postman)](https://learning.postman.com/docs/publishing-your-api/documenting-your-api/)
#
## Gerenciador de dependências Maven
[![Maven](https://skillicons.dev/icons?i=maven)](https://maven.apache.org/guides/)

## O que é Maven ?

* Maven é uma ferramenta de gerenciamento de dependências de software para projetos Java. Ele ajuda os desenvolvedores a automatizar o processo de compilação, empacotamento e distribuição de um projeto, gerenciando suas dependências de forma eficiente.

* Com o Maven, os desenvolvedores podem definir as dependências de seus projetos em um arquivo XML chamado POM (Project Object Model), que descreve as configurações do projeto, suas dependências, plugins e outras informações relevantes. O Maven é capaz de baixar automaticamente as dependências declaradas no POM de repositórios remotos, tornando o processo de gerenciamento de dependências mais fácil e rápido.
#
## Para mais informações da ferramenta
 * Documentação sobre a ferramenta em questão
    
    [![Maven](https://skillicons.dev/icons?i=maven)](https://maven.apache.org/guides/)
#

## Utilização da ferramenta

* Com o Maven inicializamos a o inicio do projeto contribuindo com dependencias que iriamos precisar para inicializar a aplicação com o Spring.

* Utilizamos as seguintes dependências.: Spring Actuator, Spring Web, Spring Boot DevTools, Spring JPA e MySQL Driver.

* Junto do Maven, nós criamos um arquivo .jar que continha todas as funções da aplicação.

#
## Ferramenta de virtualização container Docker
 [![Docker](https://skillicons.dev/icons?i=docker)](https://docs.docker.com/)

## O que é Docker ?
* Docker é uma plataforma de virtualização de contêineres que permite aos desenvolvedores criar, testar e implantar aplicativos em diferentes ambientes de forma rápida e fácil. Essa tecnologia é baseada em contêineres, que são unidades de software autônomas que contêm tudo o que é necessário para executar um aplicativo, incluindo bibliotecas, dependências e código. Independentemente do sistema operacional ou infraestrutura subjacente.
#
## Utilização da ferramenta:
* Como nós haviamos dificudade para obter a ferramenta através de nossas maquinas fisicas pois deveriamos ter acesso a senha administradora para instalar a ferramenta Docker, recorremos a utilizar uma maquina virtual(VM=Virtual Machine).

* Utilizando um sistema operacional Linux (Fedora) instalamos o Docker e a ideia inicial venho do Docker disponibilizar a nós o gerenciador de banco de dados MySQL através de uma porta dentro das configurações ambientes do container.

* Por final fomos além e transformamos toda a nossa aplicação desenvolvida em linguagem Java e transformamos a mesma em um container que poderiamos administra-lá através da maquina virtual. OBS: A aplicação estava na fisíca e agora na VM

## Para mais informações sobre a ferramenta
* Documentação sobre a ferramenta em questão

    [![Docker Documentação](https://skillicons.dev/icons?i=docker)](https://docs.docker.com/)
#
## Ferramenta de automatização Jenkins
[![Jenkins](https://skillicons.dev/icons?i=jenkins)](https://www.jenkins.io/doc/)

## O que é Jenkins ?
* Jenkins é uma ferramenta de automação de integração contínua (CI) e entrega contínua (CD) de software. Essa ferramenta é usada para automatizar o processo de construção, teste e implantação de aplicativos em diferentes ambientes, permitindo que as equipes de desenvolvimento reduzam o tempo de entrega do software e aumentem a qualidade do produto final.

* Com o Jenkins, os desenvolvedores podem configurar pipelines de integração contínua e entrega contínua que automatizam a compilação, teste e implantação de aplicativos em diferentes ambientes
#
## Utilização da ferramenta:
* Como dito antes, Jenkins é uma ferramenta de automatização, sabendo disso decidimos tornar nossa forma de construção do código uma ação automatica através de somente um botão.

* Dentro da ferramenta acessando a mesma através da porta padrão, temos o controle do painel da ferramenta, dentro dela criamos uma pipeline e dentro da mesma criamos um script de clonagem e de construção de um container que possui a imagem contida das informações do banco de dados e junto da nossa aplicação desenvolvida na linguagem Java.
#
## Para mais informações sobre a ferramenta:
 * Documentação sobre a ferramenta em questão
 
    [![Jenkins Documentação](https://skillicons.dev/icons?i=jenkins)](https://www.jenkins.io/doc/)
#
## GitHub
[![GitHub](https://skillicons.dev/icons?i=github)](https://github.com)

## O que é GitHub ? (Onde você está nesse exato momento...)

* GitHub é uma plataforma de hospedagem de código-fonte baseada na web que permite que desenvolvedores compartilhem e colaborem em projetos de software. A plataforma é baseada no sistema de controle de versão Git, que permite o rastreamento de alterações em arquivos ao longo do tempo, facilitando a colaboração e a revisão de código.
#
## Utilização da ferramenta
* Por ultimo mas não mais importante o famoso github, a ferramenta | site contribuiu para o compartilhamento da aplicação através da internet.

* Uma das diversas formas de compartilhamento que existem, nós utilizamos o GitHub, nós criamos um repositorio especifico para se dedicar a subida da aplicação movendo seus diretórios e arquivos contidos com a linguagem Java, caso queira dar uma olhada chama-se "Tarefas".

* Dentro do repositório junto das pastas e arquivos, contém também a funcionalidade de gerar uma imagem para o Docker utilizando o Maven que irá gerar um .jar dentro da maquina virtual, por meio desse .jar que o nome é setado no pom.xml, (finalName) geramos a imagem e o container.

* Resumidamente o trabalho do GitHub se auxiliou ao compartilhamento dos arquivos através de uma forma que haviamos mais facil.