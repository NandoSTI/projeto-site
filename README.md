# projeto-site

# Projeto Pearson Hardman - Site Escritório de advocacia

### Desde que comecei a aprender HTML, CSS, e JavaScript, minha jornada no mundo da programação se tornou uma experiência transformadora. Quando mergulhei no HTML, descobri uma linguagem simples e poderosa que me permitiu construir a estrutura fundamental de qualquer página da web. Aprendi a criar tags, organizar elementos e definir a aparência de textos, imagens e outros conteúdos. Com o HTML, percebi que eu poderia dar vida às minhas ideias online. Logo em seguida, adentrei o mundo do CSS. Com ele, descobri o poder de estilizar páginas da web, transformando-as em criações visualmente atraentes. Aprendi a aplicar cores, criar layouts responsivos, adicionar animações e efeitos visuais. O CSS me ensinou a expressar minha criatividade e transmitir mensagens através do design. Então, decidi mergulhar de cabeça no JavaScript. Com essa linguagem de programação, fui capaz de adicionar interatividade às minhas páginas da web. Aprendi a manipular elementos, criar eventos evalidar formulários. Ao longo desse percurso de aprendizado, enfrentei desafios e obstáculos, mas cada dificuldade superada me proporcionou um crescimento significativo. Através de cursos online, tutoriais e projetos práticos, pude aprimorar minhas habilidades e me tornar mais confiante a cada projeto concluido. Hoje, posso dizer com confiança que essas linguagens – HTML, CSS, JavaScript e TypeScript – abriu um mundo de possibilidades para mim. No entanto, o aprendizado é uma jornada contínua. Sempre busco me atualizar, acompanhar as últimas tendências e explorar novas tecnologias relacionadas ao desenvolvimento web. Sei que essa área está em constante evolução, e estou pronto para abraçar os desafios futuros e continuar expandindo meu conhecimento no desenvolvimento web.

<br>

## Índice

- [Visão geral](#visão-geral)
- [Captura de tela](#captura-de-tela)
- [Links](#links)
- [Construído com](#construído-com)
- [O que aprendi](#o-que-aprendi)
- [Desenvolvimento contínuo](#desenvolvimento-contínuo)
- [Recursos úteis](#recursos-úteis)
- [Fernando Mendes](#autor)

<br>

## Visão geral
 <br>

### Captura de tela

<br>

#### Tela Desktop

<br>

[<img src="pearsonhardmandesktop.gif" alt="Tela desktop exibindo funcionalidades">]

<br>

#### Tela Responsiva

<br>

[<img src="pearsonhardmanresponsivo.gif" alt="Exibindo responsividade em dois tamanhos de tela">]

<br>

## Links

<br>
- Site URL:[https://projeto-site-khaki.vercel.app/]

<br>

## Construído com


<div style="display: inline_block"><br>
  <img align="center" alt="Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">       
</div>
 <br>
 
## O que eu aprendi
<br>
Nesse projeto envolvendo HTML, CSS e JavaScript aprendi conceitos importantes. Através do CSS, aprendi a dar estilo e formatar elementos HTML, explorando propriedades como cores, fontes, posicionamento,animações e responsividade. 

Com JavaScript pude adicionar interatividade e dinamismo ao projeto. Com ele, aprendi a manipular elementos HTML, responder a eventos do usuário, criar animações e implementar lógica complexa.

Ao trabalhar com CSS e JavaScript em conjunto, aprendi a integrar essas duas linguagens para criar experiências ricas e interativas. Pude usar JavaScript para controlar o comportamento do CSS, modificando estilos com base em ações do usuário ou em eventos específicos.

No processo de aprendizado, foi importante entender os conceitos fundamentais de cada linguagem, como seletor de CSS, caixas-modelo, fluxo de renderização, manipulação do DOM, eventos, funções e estruturas de controle do JavaScript. Praticar esses conceitos em projetos reais nos ajuda a aprimorar nossas habilidades e explorar diferentes técnicas e soluções para os desafios que encontramos.

Concluir esse projeto, mesmo que só a primeira parte da ideia geral, me deu confiança para a construção de interfaces web cada vez mais atrativas e funcionais. 

<br>

## Trechos de códigos

<br>

``` 
JavaScript


function showSlides() {
   
    for (let i = 0; i < slides.length; i++) {
        slides[i].classList.remove("active");
        dots[i].classList.remove("active");
    }

    slideIndex++

    if(slideIndex > slides.length) {
        slideIndex = 1;
    }   

    slides[slideIndex - 1].classList.add("active");
    dots[slideIndex - 1].classList.add("active");

    setTimeout(showSlides, 3000);
}


//Eventos ---------------------------------------------------------------

[menuBtn, closeMenuBtn].forEach( (btn) => {
    btn.addEventListener("click", (e) => {
        menu.classList.toggle("menu-active");
    });
});

allLinks.forEach((link) => {
    link.addEventListener("click", smoothScroll)
});

 CSS

:root {
    --main-color: #d92123;
    --primary-text-color: #FFF;
    --secondary-text-color: #191919;
    --secondary-color: #868686;
    --tertiary-color: #eff3f4;
    --secondary-bg-color: #5c1011;

}
*{
    font-family: lato;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

a{
    text-decoration: none;
}

img{
    width: 100%;
}

HTML

  <header id="header">
        <div id="inner-header">
            <h2 id="brand">Pearson Hardman</h2>
            <nav id="navbar">
                <a href="#header">início</a>
                <a href="#expertise-areas">serviços</a>
                <a href="#about">sobre</a>
                <a href="#team">time</a>
                <a href="#contact">contato</a>
            </nav>

```
<br>

## Desenvolvimento contínuo

<br>
<br>
Pretendo continuar focado em construir um conhecimento sólido nessas linguagens. Ainda há muitos conceitos importantes para serem desenvolvidos. Todos os dias são gradativamente adicionados ao meu repertório de ferramentas novos conceitos e aprendizados.

<br>

## Recursos úteis
<br>

- [Udemy](https://www.udemy.com/) - Nessa plataforma pude fazer cursos que abriram um leque de possibidades e me ajudaram a resolver problemas e construir projetos.
- [W3School](https://www.w3schools.com/css/default.asp) - Esse site sempre me ajuda a resolver qualquer problema relacionados a códigos de uma maneira fácil e muito rápida.
- [Dev em Dobro](https://www.youtube.com/@DevemDobro) - Este é um canal onde encontro muito material. Tem muito conteúdo relacionado ao desenvolvimento. Recomendo a todos que querem aprender sobre esse e outros conceitos relacionados.

## Autor

[Fernando Mendes](https://www.linkedin.com/in/fernandomendesti/)




