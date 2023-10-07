# Orientação a Objetos e UML: Diagrama de Classes do iPhone

![UML](https://img.shields.io/badge/-UML-white?style=for-the-badge&logo=UML&color=FABD14&logoColor=white)

Este é um diagrama UML que representa a estrutura de classes e interfaces para um sistema que engloba a modelagem do iPhone, um dispositivo que incorpora funcionalidades de um reprodutor de música, um telefone e um navegador de internet. Este diagrama foi desenvolvido como parte do desafio de projeto do **Santander Bootcamp 2023 - Fullstack Java+Angular** na DIO.me.

![iPhone](https://raw.githubusercontent.com/Angeloabrita/Diagramacao-de-Classes-do-iPhone/iphone.png)

## Descrição das Interfaces e Classes

### Reprodutor Musical (ReprodutorMusical)

A interface `Reprodutor Musical` é responsável por implementar a funcionalidade de reprodução de arquivos de áudio. Ela inclui métodos como `tocar()`, `pausar()`, e `selecionarMusica()`. A classe `Musica` armazena informações relacionadas às músicas.

### Aparelho Telefônico (AparelhoTelefonico)

A interface `Aparelho Telefônico` é responsável por implementar a funcionalidade de um telefone. Ela engloba métodos como `ligar()`, `atender()`, e `iniciarCorreioVoz()`. A classe `Contato` armazena informações de contatos.

### Navegador de Internet (NavegadorInternet)

A interface `Navegador de Internet` é responsável por implementar a funcionalidade de um navegador web. Ela incorpora métodos como `exibirPagina()`, `adicionarNovaAba()`, e `atualizarPagina()`.

## Entidades

Existem diversas entidades representadas no diagrama, tais como `IPhone`, `FireFox`, `Chrome`, `Nokia 3310`, `Motorola Razr V3`, `Walkman`, e `Discman`, que representam diferentes dispositivos ou aplicativos que podem fazer uso das interfaces e classes mencionadas anteriormente.

## Como Visualizar o Diagrama

Para visualizar o diagrama UML, você pode copiar o código PlantUML e colá-lo em um editor compatível com PlantUML ou utilizar uma ferramenta online de renderização de PlantUML.

Exemplo de uso com a ferramenta PlantUML Online:
1. Acesse o site https://www.planttext.com/.
2. Cole o código PlantUML na área de texto.
3. Clique no botão "Refresh" para gerar o diagrama.