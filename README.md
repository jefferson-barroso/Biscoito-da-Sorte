
# Biscoito da Sorte - React Native

Este é um projeto simples desenvolvido em React Native, que simula a experiência de quebrar um biscoito da sorte. Ao clicar no botão, uma imagem de biscoito se "abre" e uma frase inspiradora é exibida para o usuário.

## Funcionalidades

- Exibe uma imagem de biscoito da sorte.
- Ao pressionar o botão "Quebrar Biscoito", o biscoito se "abre" e uma frase aleatória é exibida.
- As frases são inspiradoras e motivacionais.

## Tecnologias Utilizadas

- **React Native**: Biblioteca para desenvolvimento de aplicações móveis.
- **JavaScript**: Linguagem utilizada para o desenvolvimento da aplicação.
- **React**: Biblioteca para criação de componentes e gerenciamento de estados.

## Como Rodar o Projeto

### Pré-requisitos

- Ter o **Node.js** instalado. Se ainda não tiver, pode ser baixado [aqui](https://nodejs.org/).
- Ter o **Expo CLI** instalado. Caso não tenha, instale com o comando:
  bash
  npm install -g expo-cli

### Passos

1. Clone este repositório:
   git clone https://github.com/jefferson-barroso/Biscoito-da-Sorte


2. Navegue até o diretório do projeto:
   cd biscoito-da-sorte
   

3. Instale as dependências:
   npm install
   

4. Inicie o projeto com Expo:
   expo start
  

5. Abra o aplicativo no seu dispositivo móvel utilizando o aplicativo **Expo Go** (disponível na App Store ou Google Play), ou emulador.

## Estrutura do Projeto

* **App.js**: Arquivo principal da aplicação, contém a lógica e os componentes.
* **src/biscoito.png**: Imagem do biscoito fechado.
* **src/biscoitoAberto.png**: Imagem do biscoito aberto.

## Como Funciona

* O aplicativo exibe uma imagem de biscoito fechado.
* Ao clicar no botão "Quebrar Biscoito", a imagem do biscoito muda para o biscoito aberto e uma frase aleatória é exibida.
* As frases são armazenadas em um array e selecionadas aleatoriamente sempre que o botão é pressionado.
