# enhanced-tv-search

## Sumário

- [enhanced-tv-search](#enhanced-tv-search)
  - [Sumário](#sumário)
  - [Motivação](#motivação)
  - [Pilha de tecnologia](#pilha-de-tecnologia)
  - [Galeria](#galeria)
  - [Como rodar](#como-rodar)
    - [Pré-requisitos](#pré-requisitos)
    - [Passo a passo](#passo-a-passo)

## Motivação

<details>
  <summary>
    <strong>Spoiler</strong>
  </summary>
    
A avaliação final desta unidade curricular consistiu em requintar este app e está disponível [aqui](https://github.com/mdccg/enhanced-tv-search/).
</details>

Este app é um cliente básico do catálogo de shows de TV [TVmaze](https://www.tvmaze.com/).

Vale destacar que parte do app foi desenvolvida pelo professor e a atividade consistiu em finalizá-lo, adicionando a página de detalhes de um show de TV e o filtro de pesquisa pendente.

Este foi o segundo repositório de código apresentado no [Curso Superior de TSI do IFMS](https://www.ifms.edu.br/campi/campus-aquidauana/cursos/graduacao/sistemas-para-internet/sistemas-para-internet) como requisito para obtenção da nota parcial das atividades da unidade curricular Construção de Páginas Web II.

## Pilha de tecnologia

As seguintes tecnologias foram utilizadas para desenvolver este app:

| Papel | Tecnologia |
|-|-|
| Ambiente de execução | [Node](https://nodejs.org/en/) |
| Linguagem de programação | [TypeScript](https://www.typescriptlang.org/) |
| Ambiente de desenvolvimento | [Vite](https://vitejs.dev/) |
| Base de dados | [TVmaze](https://www.tvmaze.com/api) |

## Galeria

![Página inicial](./docs/home-page.png)
![Resultados para "Hulk"](./docs/results-for-hulk.png)
![Detalhes de Hulk](./docs/tv-show-details.png)

## Como rodar

### Pré-requisitos

- [Node](https://nodejs.org/en/download/);
- [Yarn](https://yarnpkg.com/) (opcional).

### Passo a passo

1. Clone o repositório de código em sua máquina;
   
2. Abra um shell de comando de sua preferência (prompt de comando, PowerShell, terminal _etc_.);

3. Instale as dependências do projeto através do seguinte comando:

```console
$ npm install
```

Caso esteja utilizando o gerenciador de pacotes Yarn, execute o seguinte comando como alternativa:

```console
$ yarn
```

4. Finalmente, execute o seguinte comando para iniciar o app:

Para npm:

```console
$ npm run dev
```

Para Yarn:

```console
$ yarn dev
```