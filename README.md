# Manipulando_JSON

Este repositório contém um projeto focado na manipulação de dados JSON, oferecendo busca, filtragem e ordenação em listas de objetos. Ele é ideal para lidar com informações estruturadas, como dados de estudantes.

## Arquivos do Projeto

### `encontra_estudantes.js`
- Realiza buscas específicas em um arquivo JSON (`estudantes.json`).
- Utiliza a função `buscaInformacao` para localizar informações por chave e valor, retornando o primeiro resultado encontrado.

### `filtrar_estudantes.js`
- Filtra estudantes baseando-se na ausência de propriedades específicas nos endereços cadastrados.
- Utiliza a função `filtraPorPropriedades` para gerar uma lista de estudantes com endereços incompletos.

### `ordenar_estudantes.js`
- Ordena os estudantes com base em uma propriedade específica, como `nome` ou `telefone`.
- Utiliza a função `ordena` para reorganizar os dados de forma crescente.

### `estudantes.json`
- Arquivo JSON que contém dados de estudantes, incluindo:
  - Nome
  - Email
  - Telefones
  - Endereço (com propriedades como logradouro, número, cep e complemento)

## Funcionalidades

- **Busca por informações específicas**: Localize estudantes com base no nome ou telefone usando `encontra_estudantes.js`.
- **Filtragem de endereços incompletos**: Liste estudantes cujos endereços não possuem determinada propriedade usando `filtrar_estudantes.js`.
- **Ordenação de estudantes**: Organize os dados dos estudantes por propriedades específicas, como nome ou telefone, utilizando `ordenar_estudantes.js`.

## Pré-requisitos

- **Node.js** instalado no sistema.

## Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/manipulando_json.git
