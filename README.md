Esse repositório é um fork Piggy Metrics [link], uma aplicação de referência que demonstra a adoção de uma arquitetura de microserviços usando o framework Spring Cloud (link) e Docker

# Desafio:

Subir uma Jenkins que será o servidor de CI /CD
Construir uma pipeline com ao menos os seguintes steps:
build:maven
test:maven
package:docker
install:docker

Submeter alguma alteração no código fonte, será esperado que o pipeline execute e a nova versão da aplicação seja instalada em alguma infraestrutura (local ou cloud)

Opcional: adicionar um stage para análise da qualidade do código fonte
Opcional: analisar um stage para instalação dos artefatos (jar e docker) em um repositório
