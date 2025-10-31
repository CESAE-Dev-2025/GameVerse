<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Unlicense License][license-shield]][license-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/cesae-dev-2025/GabeVerse/">
    <img src="images/logo.svg" alt="Logo" height="70">
  </a>
  
  

  <p align="center">Um universo de conteúdo para a comunidade Gamer!
    <br />
    <a href="https://cesae-dev-2025.github.io/GameVerse/"><strong>Veja a Demo</strong></a>
    <br />
  </p>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Índice</summary>
  <ol>
    <li>
      <a href="#sobre-o-projecto">Sobre o Projecto</a>
      <ul>
        <li><a href="#tecnologias-utilizadas">Tecnologias utilizadas</a></li>
        <li><a href="#capturas-de-ecra">Capturas de ecrã</a></li>
      </ul>
    </li>
    <li>
      <a href="#como-utilizar">Como utilizar</a>
      <ul>
        <li><a href="#pre-requisitos">Pré-requisitos</a></li>
        <li><a href="#instalação">Instalação</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">Licença</a></li>
    <li><a href="#contacto">Contacto</a></li>
    <li><a href="#agradecimentos">Agradecimentos</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## Sobre o Projecto

![Gameverse Screenshot][product-screenshot]

Esse projeto apresenta um website de comunidade Gamer. É composto pelas seguintes páginas:

1. **Página Inicial**: Apresentação da comunidade, jogos populares em destaque e eventos futuros.
2. **Jogos**: Listagem de jogos populares com descrições, links para compra ou download, e guias básicos para
iniciantes.
3. **Eventos e Torneios**: Página dedicada a eventos, competições e torneios organizados pela comunidade, com
cronogramas e opções de inscrição online.
4. **Fórum**: Seção ~~interativa~~ (em construção) onde os membros podem criar tópicos, discutir estratégias, compartilhar dicas e interagir.
5. **Loja**: Loja virtual com mercadorias da comunidade (camisetas, acessórios, etc.) e produtos digitais como
wallpapers exclusivos.
6. **Contato**: Formulário para contato com os administradores e informações de redes sociais e canais da
comunidade.

### Capturas de ecrã

#### Web

<p style="display: flex; justify-content: space-between; align-items: start;">
  <img src="images/GameVerse_home.png" style="width: 45%;" alt="Página inicial">
  <img src="images/GameVerse_games.png" style="width: 45%;" alt="Jogos">
</p>
<br>
<p style="display: flex; justify-content: space-between;">
  <img src="images/GameVerse_events.png" style="width: 45%;" alt="Eventos">
  <img src="images/GameVerse_forum.png" style="width: 45%;" alt="Fórum">
</p>
<br>
<p style="display: flex; justify-content: space-between;">
  <img src="images/GameVerse_store.png" style="width: 45%;" alt="Loja">
  <img src="images/GameVerse_contact.png" style="width: 45%;" alt="Contato">
</p>

#### Mobile

<p style="display: flex; justify-content: space-between;">
  <img src="images/GameVerse_home_mobile.png" style="width: 30%;" alt="Página inicial">
  <img src="images/GameVerse_games_mobile.png" style="width: 30%;" alt="Jogos">
  <img src="images/GameVerse_events_mobile.png" style="width: 30%;" alt="Eventos">
</p>
<br>
<p style="display: flex; justify-content: space-between;">
  <img src="images/GameVerse_forum_mobile.png" style="width: 30%;" alt="Fórum">
  <img src="images/GameVerse_store_mobile.png" style="width: 30%;" alt="Loja">
  <img src="images/GameVerse_contact_mobile.png" style="width: 30%;" alt="Contato">
</p>

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>


### Tecnologias utilizadas

Este projeto foi desenvolvido com uso das tecnologias listadas abaixo, a partir de um layout do Figma ([https://www.figma.com/make/RTOukb07RLih0oaiRRV9Sk/Gaming-Community-Website?node-id=0-1&p=f&t=4qJdik9Wt1qBX8LH-0](https://www.figma.com/make/RTOukb07RLih0oaiRRV9Sk/Gaming-Community-Website?node-id=0-1&p=f&t=4qJdik9Wt1qBX8LH-0)).

<!-- TODO: Add used APIs (for map and mail service) -->
<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/DiceBear-3b3b3b?style=for-the-badge&logo=dicebear&logoColor=white" alt="DiceBear">
  <!-- <img src="https://img.shields.io/badge/GoogleMaps_API-blue?style=for-the-badge&logo=googlemaps&logoColor=white" alt="GoogleMaps API"> -->
</p>

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>


<!-- GETTING STARTED -->
## Como utilizar

Para utilizar este projeto, basta clonar o repositório e consguir uma API do Google Maps ou substituí-la por outro serviço.

### Pré-requisitos

É preciso ter o Git instalado.

### Instalação

<!-- TODO: especificar API keys necessárias -->

1. Consiga uma API Key em [https://console.cloud.google.com/](https://console.cloud.google.com/)
2. Clone o repositório
   ```sh
   git clone https://github.com/CESAE-Dev-2025/GameVerse.git
   ```
3. Entre com sua API em `script.js`, logo acima da definição da variável `map`
   ```js
   key: "ENTER YOUR API",
   ```
4. Modifique a URL do git remote para evitar `pushes` acidentais para o projeto base
   ```sh
   git remote set-url origin github_username/repo_name
   git remote -v # confirm the changes
   ```

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>


<!-- ROADMAP -->
## Roadmap

- [x] Adicionar API do Google Maps
- [x] Adicionar mais localizações
- [x] Criar a Loja
- [ ] Utilizar um Framework que permita reaproveitar componentes
- [ ] Adicionar interatividade ao Fórum
- [ ] Adicionar interatividade com o carrinho de compras da loja

Veja os ['issues' abertos](https://github.com/cesae-dev-2025/GameVerse/issues) para obter uma lista completa e atualizadas das funcionalidades propostas e bugs conhecidos.

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>


<!-- LICENSE -->
## License

Distribuido sob a Licença Unlicense. veja `LICENSE.txt` para mais informações.

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>


<!-- CONTACT -->
## Contact

José Pinho - [GitHub][github-jose-url]

Leandro Gabriel - [GitHub][github-leandro-url]

Ricardo Golegã - [GitHub][github-ricardo-url]

Link do Projeto: [https://github.com/CESAE-Dev-2025/GameVerse](https://github.com/CESAE-Dev-2025/GameVerse)

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Agradecimentos

Agradeçemos ao [CESAE](https://cesaedigital.pt/fldrSite/default.aspx) pela oportunidade de crescimento e à [Lais Reis](https://github.com/laisreis04) pelo desafio.

Agradeço também aos mantenedores dos projetos listados abaixo:
<!-- TODO: Adicionar links das APIs utilizadas para mapa e envio de email -->
* [Choose an Open Source License](https://choosealicense.com)
* [Best README Template](https://github.com/othneildrew/Best-README-Template)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Bootstrap](https://getbootstrap.com)
* [DiceBear](https://github.com/dicebear/dicebear)
<!-- * [Google Maps API](https://developers.google.com/maps/documentation/javascript/) -->

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[product-screenshot]: ./images/index-hero-bg.png
[contributors-shield]: https://img.shields.io/github/contributors/CESAE-Dev-2025/GameVerse.svg?style=for-the-badge
[contributors-url]: https://github.com/CESAE-Dev-2025/GameVerse/graphs/contributors

[license-shield]: https://img.shields.io/github/license/CESAE-Dev-2025/GameVerse.svg?style=for-the-badge
[license-url]: https://github.com/CESAE-Dev-2025/GameVerse/blob/master/LICENSE.txt

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=blue
[linkedin-url]: https://linkedin.com/in/leandro-assis-gabriel

[github-jose-url]:https://github.com/josepinho22
[github-leandro-url]:https://github.com/lassisg
[github-ricardo-url]:https://github.com/RicardoBu

[HTML5]: https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
[HTML5-url]: https://developer.mozilla.org/pt-BR/docs/Web/HTML
[CSS3]: https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white
[CSS3-url]: https://developer.mozilla.org/pt-BR/docs/Web/HTML
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[Javascript]: https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black
[Javascript-url]: https://developer.mozilla.org/pt-BR/docs/Web/JavaScript 
