# Weather App

## Conteúdo

- [Sobre](#about)
- [Inciando o Projeto](#getting_started)
- [Uso](#usage)
- [Ferramentas](#tools)

## Sobre <a name = "about"></a>

Aplicação de previsão do tempo que consome a API externa [Open Weather Map](https://openweathermap.org/api). Este projeto tem propósito de ser um modo de por em prática os conhecimentos de React Hooks.

## Iniciando o Projeto <a name = "getting_started"></a>

### Pré-requisitos

- Instalar uma ferramenta de git ([normal](https://git-scm.com/download/win), [git bash](https://gitforwindows.org/), [GitHub Desktop](https://desktop.github.com/))
- Realizar um clone do projeto `git clone git@github.com:christiantld/weatherApp-react.git`
- Navegar até a pasta do projeto

### Instalando

Para inicializar o arquivo `package.json` e instalar todas as dependências digite os comandos abaixo

```
npm install
```

ou se preferir

```
yarn install
```

### Inicializando o projeto

Basta rodar o comando abaixo e uma nova aba com a aplicação irá abrir no seu navegador

```
yarn start
```

## Uso <a name="usage"></a>

Com a aplicação aberta no seu navegador basta digitar o nome da cidade que deseja buscar a previsão do tempo, clicar `enter`e a API irá retornar com os resultados.

### TO DO

- Traduzir a resposta da API
- Buscar a localização do usuário atraves da geolocalização do browser
- Inserir mais opções de backgrounds que se adequem as previsões do tempo

## Ferramentas <a name = "built_using"></a>

- React com Hooks
- Axios
- [Open Weather Map](https://openweathermap.org/api).
