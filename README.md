# Projeto-Api-REST-Com-Swagger
Uma api simples contendo todo o modelo de arquitetura rest. 
documentada pelo framework swagger

# O que é uma API REST 

O que é API?
Uma API é um conjunto de definições e protocolos usado no desenvolvimento e na integração de aplicações. Às vezes, as APIs são descritas como um contrato entre um provedor e um usuário de informações, estabelecendo o conteúdo exigido pelo consumidor (a chamada) e o conteúdo exigido pelo produtor (a resposta). Por exemplo, o design da API de um serviço meteorológico pode especificar que o usuário forneça um CEP e o produtor responda em duas partes, a primeira contendo a temperatura mais elevada e a segunda com a temperatura mais baixa.  

Em outras palavras, ao interagir com um computador ou sistema para recuperar informações ou executar uma função, a API ajudará a comunicar o que você quer ao sistema para que ele entenda e realize o que foi solicitado. 

Pense nas APIs como um mediador entre os usuários ou clientes e os recursos ou serviços web que eles querem obter. As APIs também servem para que organizações compartilhem recursos e informações e, ao mesmo tempo, mantenham a segurança, o controle e a obrigatoriedade de autenticação, pois permitem determinar quem tem acesso e o que pode ser acessado. 

Outra vantagem de usar APIs é que não é necessário saber todos os detalhes sobre o armazenamento em cache, como os recursos são recuperados ou qual é a origem deles.

# O que é o swagger 
O Swagger é um framework composto por diversas ferramentas que, independente da linguagem, auxilia a descrição, consumo e visualização de serviços de uma API REST. 

No framework Swagger, existem ferramentas para os seguintes tipos de tarefas a serem realizadas para o completo desenvolvimento da API de um serviço WEB: 

A especificação da API consiste em determinar os modelos de dados que serão entendidos pela API e as  funcionalidades presentes na mesma. Para cada funcionalidade, é preciso especificar o seu nome, os parâmetros que devem ser passados no momento de sua invocação e os valores que irão ser retornados aos usuários da API. Entre esta ferramentas, podemos citar o OpenAPI Specification.

Após especificar a API, o framework facilita sua implementação, com a ferramenta Swagger Codegen é possível montar o código inicial automaticamente nas principais linguagem de programação.

Os testes de API são extremamente importantes, pois ajudam a garantir o funcionamento, o desempenho e a confiabilidade da sua aplicação. O Swagger oferece ferramentas para teste manuais, automatizados e de desempenho 

Para auxiliar na utilização da API, o Swagger dispõe de ferramenta para deixar a visualização mais intuitiva, permitindo também que interajam com a API.

O Swagger permite criar a documentação da API de 3 formas:

Automaticamente: Simultaneamente ao desenvolvimento da API é gerada a documentação.

Manualmente: Permite ao desenvolvedor escrever livremente as especificações da API e as publicar posteriormente em seu próprio servidor.

Codegen: Converte todas as anotações contidas no código fonte das APIs REST em documentação.
