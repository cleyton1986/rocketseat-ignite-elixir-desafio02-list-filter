<p align="center">
  <img  src="./assets/cover-elixir.png">
</p>

<h1 align="center">
  Ignite (Elixir) - Rocketseat
</h1>

<h3 align="center">
  Desafio: Filtragem em listas
</h3>

<blockquote align="center">“Tudo deveria se tornar o mais simples possível, mas não simplificado - Albert Einstein”!</blockquote>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/cleyton1986/rocketseat-ignite-elixir-desafio01-using-recursion?color=%2304D361">

  <a href="https://www.linkedin.com/in/cleytonalves">
    <img alt="Made by Cleyton" src="https://img.shields.io/badge/Made%20by-Cleyton_Alves-Alves%2304D361">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">

  <a href="https://github.com/cleyton1986/rocketseat-ignite-elixir-desafio01-using-recursion/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/cleyton1986/rocketseat-ignite-elixir-desafio01-using-recursion?style=social">
  </a>
</p>

<p align="center">
  <a href="#tecnologias-e-recursos">Tecnologias e Recursos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#rotas-da-aplicação">Rotas da aplicação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#específicação-dos-testes">Especificação de testes</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#instalação-e-execução">Instalação e execução</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#arquivo-do-insomnia">Arquivo do Insomnia</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#calendar-entrega">Entrega</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>


## Tecnologias e recursos

- [Elixir](https://elixir-lang.org/install.html)

## Sobre o desafio

Nesse desafio, você deverá criar um novo projeto com uma função que, dada uma lista de strings que representem números ou não (exemplo `["1", "3", "6", "43", "banana", "6", "abc"]`), filtre todos os elementos numéricos da lista e retorne quantos números ímpares existem nessa lista.

Diferente do desafio 01, a sua solução para esse desafio não precisa ser recursiva. Sinta-se livre para criar a solução da melhor maneira que achar

(veja a dica sobre o 
    <a href="https://www.notion.so/Testes-test-list_length_test-exs-beef33b644d644d2aa11b29840f19864">🔗 módulo Enum </a>
) 🚀

Para isso, você pode iniciar um projeto usando o comando:


``
mix new list_filter
``

O nome do projeto pode ser um de sua escolha  💜

## Específicação dos testes

Podemos acompanhar o resultado esperado observando o seguinte exemplo de execução da função:

``
iex> ListFilter.call(["1", "3", "6", "43", "banana", "6", "abc"])
...> 3

Você deve cumprir para que o teste passe.


<h1 align="left">
    <a href="https://www.notion.so/Testes-test-list_length_test-exs-beef33b644d644d2aa11b29840f19864">🔗 Exemplo</a>
</h1>

## :calendar: Entrega

Esse desafio foi entregue na plataforma Skylab - Rocketseat.

<p align="center">
  <img  src="./assets/test-result.png">
</p>

## Instalação e execução

```bash
# OBS.: ANTES DE PROCEDIMENTO, CERTIFIQUE-SE QUE O ELIXIR ESTEJA INSTALADO NO SEU COMPUTADOR CORRETAMENTE.

# Clone esse repositório
$ git clone https://github.com/cleyton1986/rocketseat-ignite-elixir-desafio02-list-filter

# Entre no diretório
$ cd rocketseat-ignite-elixir-desafio02-list-filter

# entre na pasta
$ cd list_filter

# para compilar o projeto, execute o comando
$ mix compile

# para rodar os testes, execute o comando
$ mix test
```


## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

 implementado por 👨🏽‍💻 Cleyton Alves e desenvolvido 💜 by Rocketseat.
