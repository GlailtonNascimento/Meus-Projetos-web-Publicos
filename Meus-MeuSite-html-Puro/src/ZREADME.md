# Meu Portfólio Web

[![Linguagens](https://img.shields.io/badge/Linguagens-HTML%20%7C%20CSS%20%7C%20JavaScript-informational?style=flat-square)](https://skillicons.dev/icons?i=html,css,javascript)
[![Ícones](https://img.shields.io/badge/Ícones-Bootstrap%20Icons-informational?style=flat-square)](https://icons.getbootstrap.com/)
[![EmailJS](https://img.shields.io/badge/Email-EmailJS-informational?style=flat-square)](https://www.emailjs.com/)

Este é o meu portfólio web pessoal, desenvolvido com HTML, CSS e JavaScript, utilizando ícones do Bootstrap Icons e a biblioteca EmailJS para o formulário de contato.

## Ideia do Projeto

A ideia central deste projeto é criar um espaço online profissional e interativo para apresentar minhas habilidades, experiências e projetos de desenvolvimento web. O portfólio visa ser uma vitrine do meu trabalho, facilitando que recrutadores, colaboradores e outros interessados conheçam meu perfil, minhas especialidades e entrem em contato comigo.

## Objetivo do Projeto

* **Apresentar minhas habilidades:** Demonstrar proficiência em tecnologias front-end (HTML, CSS, JavaScript) e conhecimentos em back-end (Java, Python, PHP e seus respectivos frameworks) e bancos de dados SQL.
* **Mostrar meus projetos:** Exibir os projetos que desenvolvi, com destaque para o código no GitHub e a possibilidade de visualização online (quando aplicável).
* **Fornecer informações sobre minha trajetória:** Compartilhar minha transição para a área de tecnologia, experiências prévias relevantes e minha busca por aprendizado contínuo.
* **Facilitar o contato:** Oferecer um formulário de contato direto e links para minhas redes sociais profissionais (LinkedIn, GitHub, Instagram) e WhatsApp.
* **Criar uma experiência de usuário agradável:** Proporcionar uma navegação intuitiva, um design responsivo e interações dinâmicas que engajem o visitante.

## Tecnologias Utilizadas

* **HTML5:** Estrutura semântica da página e organização do conteúdo.
* **CSS3:** Estilização visual, layout responsivo, animações e transições.
* **JavaScript:** Interatividade, manipulação do DOM, funcionalidades dinâmicas (menu mobile, efeito de digitação, animação de projetos, mostrar/ocultar seções) e integração com a biblioteca EmailJS.
* **Bootstrap Icons:** Utilizado para fornecer ícones vetoriais para melhorar a experiência visual.
* **EmailJS:** Biblioteca JavaScript para enviar e-mails diretamente do lado do cliente, utilizada no formulário de contato.

## Estrutura da Página (`index.html`)

O portfólio é composto pelas seguintes seções principais:

* **`header`:**
    * Contém o menu de navegação principal (desktop e mobile).
    * Logotipo do portfólio.
    * Ícone de menu para dispositivos móveis.
    * Título "Portfólio" centralizado.
* **`section#Inicio` (Topo do Site):**
    * Apresentação principal com saudação, nome completo, profissão com efeito de digitação, links para download do currículo e contato, e foto de perfil com link para o GitHub.
* **`section#Sobre` (Sobre):**
    * Seção para apresentar informações pessoais, trajetória na tecnologia, experiências, estudos e certificações (com opção de "Ver Mais").
    * Links para redes sociais profissionais.
* **`section#Especialidade` (Especialidades):**
    * Destaque das habilidades e tecnologias de conhecimento (front-end, back-end e bancos de dados), com opção de "Ver Mais" para exibir a lista completa.
* **`section#Projetos` (Portfólio):**
    * Exibição dos projetos, utilizando um layout de grid responsivo.
    * Cada projeto pode conter um slider de imagens e um overlay com título, descrição e links para o código e visualização online.
* **`section#Contato` (Formulário):**
    * Formulário para os visitantes entrarem em contato diretamente, utilizando EmailJS para o envio.
    * Mensagem de confirmação ou erro após o envio.
* **`footer`:**
    * Informações de contato (e-mail) e links para redes sociais.
    * Botão "Voltar ao Topo" fixo.
* **Menu Mobile (`#menu-mobile`):**
    * Menu lateral responsivo para navegação em dispositivos móveis.
* **Overlay do Menu (`.overlay-menu`):**
    * Camada escura que aparece ao abrir o menu mobile.
* **Botão "Voltar ao Topo" Fixo (`#btn-inicio-fixo`):**
    * Botão flutuante para retornar facilmente ao início da página.

## Estilos (CSS - `style.css`)

O design e a apresentação visual do meu portfólio foram cuidadosamente elaborados utilizando CSS3. As principais características do estilo incluem:

* **Paleta de Cores:** Uma paleta escura predominante (#000000, #13131F, #212121, #1a1a1a) com destaque para uma cor roxa vibrante (#8257E6) utilizada em elementos interativos, títulos e detalhes importantes.
* **Tipografia:** A fonte principal utilizada é a 'DM Sans' (do Google Fonts), com pesos e estilos variados para diferentes elementos. A fonte 'Poppins' também é utilizada para títulos e links do menu, conferindo um toque moderno.
* **Layout Responsivo:** O portfólio foi desenvolvido com foco na responsividade, utilizando media queries para adaptar o layout a diferentes tamanhos de tela (desktop, tablets e dispositivos móveis). Isso garante uma experiência de usuário consistente em diversos dispositivos.
* **Cabeçalho Fixo:** O cabeçalho principal permanece fixo no topo da tela, facilitando a navegação entre as seções do portfólio.
* **Menu Mobile:** Um menu hambúrguer é implementado para dispositivos móveis, proporcionando uma navegação otimizada em telas menores.
* **Animações e Transições:** Diversas animações e transições suaves foram aplicadas para melhorar a interatividade e o engajamento do usuário, como o efeito de digitação no título, a animação de flutuação da imagem de perfil e as transições de hover nos links e botões.
* **Seções Distintas:** Cada seção do portfólio (Início, Sobre, Especialidades, Projetos, Contato e Rodapé) possui estilos específicos para destacar seu conteúdo e criar uma hierarquia visual clara.
* **Especialidades:** A seção de especialidades utiliza um layout flexível para exibir as habilidades e tecnologias de forma organizada, com um botão "Ver Mais" para expandir a descrição de cada item.
* **Portfólio de Projetos:** Os projetos são apresentados em um layout de grid responsivo, com um efeito de overlay ao passar o mouse que exibe informações sobre o projeto e links para o código e visualização online. Alguns projetos utilizam um efeito de slider de imagens.
* **Formulário de Contato:** Um formulário estilizado permite que os visitantes entrem em contato diretamente.
* **Botão "Voltar ao Topo":** Um botão fixo no canto inferior direito facilita o retorno ao início da página.
* **Design Dark:** O tema predominante é escuro, com cores de texto claras para garantir a legibilidade e um visual moderno.

## Funcionalidades (JavaScript)

O JavaScript foi utilizado para adicionar interatividade e dinamismo ao portfólio, proporcionando uma melhor experiência para o usuário. As principais funcionalidades implementadas são:

* **Menu Mobile:** Abre e fecha o menu lateral para navegação em dispositivos móveis, com suporte para fechamento via tecla "Escape".
* **Efeito de Digitação:** Aplica um efeito de digitação animado ao título principal na seção "Início".
* **Animação das Imagens dos Projetos:** Pausa a animação de slider e exibe o overlay de informações ao passar o mouse nos projetos com múltiplas imagens.
* **Mostrar/Ocultar Especialidades:** Permite expandir e recolher a lista de especialidades na seção correspondente.
* **Mostrar/Ocultar Informações "Sobre":** Expande e recolhe a seção com mais detalhes sobre o autor.
* **Envio de Formulário de Contato com EmailJS:** Envia os dados do formulário de contato diretamente para o e-mail do autor, exibindo mensagens de confirmação ou erro.

## Como Visualizar

Para visualizar o portfólio, basta abrir o arquivo `index.html` em um navegador web. O design responsivo garante uma boa experiência em diferentes dispositivos.

## Contato

* [Meu LinkedIn](https://www.linkedin.com/in/glailton-nascimento/)
* [Meu E-mail](glailtonprogramador88@gmail.com)
* [Meu GitHub](https://github.com/GlailtonNascimento)
* [Meu Instagram](https://www.instagram.com/glailtonnascimento.dev/)
* [Meu WhatsApp](https://wa.me/message/JDVDLSTRHDPVI1)

## Autor

Glailton Santana do Anna Nascimento

## Licença

[[MIT License](LICENSE)]
