 # Restaurante Sabor & Arte
 
 Site oficial do **Restaurante Sabor & Arte**, um lugar onde o sabor encontra a criatividade. O site apresenta as principais seções: Início, Sobre Nós, Menu, Galeria e Contato, tudo organizado em uma interface moderna e responsiva.
 
 ## 🚀 Funcionalidades
 
 - Navegação intuitiva e fixa no topo
 - Seção "Sobre Nós" com apresentação do restaurante
 - Exibição do menu com imagens e preços dos pratos
 - Galeria de imagens de alta qualidade para apresentar o ambiente e pratos
 - Layout responsivo, adaptando-se para dispositivos móveis
 - **Scroll suave** ao clicar nos links do menu, para uma experiência mais fluida
 
 ## 💻 Tecnologias utilizadas
 
 - HTML5
 - CSS3 (com Grid e Flexbox)
 - JavaScript: Implementação do scroll suave para navegação interna
 
 ## 🧩 JavaScript
 
 No arquivo `scripts.js`, há o seguinte código para implementar o scroll suave:
 
 ```js
 document.querySelectorAll('nav a').forEach(anchor => {
     anchor.addEventListener('click', function(e) {
         e.preventDefault();
         document.querySelector(this.getAttribute('href')).scrollIntoView({
             behavior: 'smooth'
         });
     });
 });
 ```
 
 ## 📂 Estrutura do projeto
 
 - `index.html`: arquivo principal do site
 - `css.css`: estilos do site
 - `scripts.js`: script para navegação suave no menu
- Pasta `img/`: imagens dos pratos e galeria
