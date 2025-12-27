# Frontend Mentor - Huddle landing page with single introductory section solution   

Essa é a resolução do desáfio proposto [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0).  Através do Frontend Mentor, com a finalidade de por em prática meus aprendizados de HTML e CSS.

## Tabela de Conteúdo

  - [Visão Geral](#O-Desafio)
  - [O Desafio](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Construido Com](#Construido-Com)
  - [O que aprendi](#O-Que-Aprendi)
  - [Desenvolvimento continuo](#Desenvolvimento-Continuo)
  - [Recursos Utilizados](#Recursos-Utilizados)
  - [Autor](#Autor)

## Visão Geral

### O Desafio

O usuário deve conseguir:

- Ver de maneira otimizada o layout da página dependendo do tipo da tela do dispositivo que estiver usando. (Celular, Computador, Tablet...)
- Ver os estados de hover de todos os elementos que forem interativos.

### Screenshot

<p>Versao Desktop</p>

![](/images/Desktop-version.png)

<p>Versão Mobile</p>

![](/images/Mobile-version.png)

### Links

- URL da Solução: ( https://wallissondev.github.io/frontend-mentor-huddle-landing-page/ )

### Construido Com

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first

### O Que Aprendi

De todas as formas de aprender, praticar o que estudamos é a mais eficiente, nesse projeto consegui me aperfeiçoar em compreender o comportamento do flexbox, asssim como a manipulação de imagens, organização de tags com enfasê no sentido semântico. Tive que reestrutrurar meu HTML inúmeras vezes conforme eu via a necessidade de deixar ele mais organizado e coerente, ainda assim, sei que ainda tem muitos pontos de melhoria, mas fico alegre com o resultado, levando em consideração que também evitei a utilização de qualquer ferramente de IA para facilitar (sei que é uma ferramente crucial, mas não gostaria de depender dela para procurar respostas, onde a busca me faria aprender mais, do que só pegar a resposta pronta).

Vejamos alguns pontos chaves que me orgulho:

```html
<main id="fatherContainer">

      <img src="images/illustration-mockups.svg" alt="Mockups-Ilustration" id="ilustrationImage">

      <div id="asideContent">
        <h1>
          Build The Community Your Fans Will Love
        </h1>
        <p id="textContent">
          Huddle re-imagines the way we build communities. You have a voice, but so does your audience.
          Create connections with your users as you engage in genuine discussion.
        </p>
        <input type="button" value="Register" id="registerButton">
      </input>
      </div>
  </main>
```
```css
div#asideContent{
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin: 10px;
}
```

### Desenvolvimento Continuo

Levando em consideração pontos de melhorias, continuo meu desenvolvimento em HTML e CSS, buscando aperfeiçoar aspectos como o flexbox e grid layout, assim como, a manipulação de imagens, tags semânticas, propriedas e valores, pois muitas vezes, mesmo sabendo que tenho o conhecimento, tive que voltar a pesquisar para colocar esse desafio em prática.

### Recursos Utilizados

- [Flexbox Froggy](https://flexboxfroggy.com/) - É um site construído na intenção de praticar os conceitos de flexbox, não utilizei durante a construção do projeto, porém antes de iniciar, pratiquei diversas vezes e ele me ajudou a ter um certo domínio das principais propriedades e valores.

## Autor

- Website (Portfolio) - [Wallisson Moreira](https://wallissondev.github.io/projeto-portfolio/)
- Instagram - [@wallisson_lima_](https://www.instagram.com/wallisson_lima_/)
