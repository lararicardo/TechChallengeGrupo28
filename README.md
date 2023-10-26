<h1 align="center">:file_cabinet: Tech Challenge Grupo 28</h1>

## :memo: Descrição do Problema
Uma loja de roupas em São Paulo, que tem uma grande demanda de pedidos online, está enfrentando problemas para entregar seus produtos aos clientes. A loja não possui um sistema de logística eficiente para gerenciar as entregas e os clientes estão insatisfeitos com a demora na entrega.

## :memo: Descrição do Impacto
A demora na entrega está impactando negativamente a satisfação dos clientes e pode levar à perda de vendas. Além disso, a loja está perdendo oportunidades de crescimento, pois não consegue atender à demanda de pedidos online.

## :memo: Descrição da Solução
A loja precisa implementar um sistema de logística eficiente que possa gerenciar as entregas de forma eficaz. Esse sistema deve incluir as seguintes funcionalidades:

* Cadastro de clientes: O sistema deve ser capaz de obter os cadastros de lojas.
* Gerenciamento de pedidos: O sistema deve ser capaz de rastrear os pedidos até a entrega.
* Notificação do fluxo de entrega: O sistema deve fornecer aos clientes um status atualizado.

## :books: Funcionalidades
* <b>Cadastro de clientes</b>: Através de uma interface web o cliente realiza o cadastro de sua loja.

* <b>Gerenciamento de pedidos</b>: Através da API existe a integração com a loja, sendo repassado a coleta e o sistema backend realiza o processo de triagem

* <b>Notificação do fluxo de entrega</b>: Dentro do sistema backend existe rotinas que realizam o acompanhamento do fluxo e notificação ao cliente via e-mail.

* <b>Gerenciamento de dados</b>: Funcionalidades responsáveis pelo manuseio dos dados de clientes, pacotes e entrega. Sendo os dados armazenados em banco de dados H2.

## :wrench: Tecnologias utilizadas
* Java, H2, Spring Boot, Maven e Angular.

## :rocket: Rodando o projeto
Para rodar o repositório é necessário clonar o mesmo, dar o seguinte comando para iniciar o projeto:
```
<linha de comando>
```

<br> cd /opt/ </br>
<br> git clone {URL_DO_REPOSITÓRIO} </br>
<br> cd {NOME_PROJETO} </br>
<br> ./mvnw spring-boot:run </br>
<br> curl -Ivvv http://localhost:8080/api/clientes </br>

## :soon: Implementação futura

Cadastro de clientes (Camada de apresentação).

## :handshake: Colaboradores
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/DouglasPFS">
        <img style="height:auto;" src="https://avatars.githubusercontent.com/u/18017521?s=400&amp;u=6fcd8bd5ed6088d6f752ee31f32ec3a92875c87c&amp;v=4" width="200" height="200" class="avatar avatar-user width-full border color-bg-default" alt="@DouglasPFS">
        <sub>
          <br>Douglas R. Moreira</br>
        </sub>
      </a>
    </td>
	<td align="center">
      <a href="https://github.com/lararicardo">
        <img style="height:auto;" src="https://avatars.githubusercontent.com/u/5578401?v=4" width="200" height="200" class="avatar avatar-user width-full border color-bg-default" alt="@lararicardo's">
		<sub>
          <br>Ricardo R. Lara</br>
        </sub>
      </a>
    </td>
	<td align="center">
      <a href="https://github.com/devopsjeffersantos">
        <img style="height:auto;" src="https://avatars.githubusercontent.com/u/117692262?v=4" width="200" height="200" class="avatar avatar-user width-full border color-bg-default" alt="@devopsjeffersantos's">
		<sub>
          <br>Jefferson R. Santos</br>
        </sub>
      </a>
    </td>
  </tr>
</table>

## :dart: Status do projeto# TechChallengeGrupo28
