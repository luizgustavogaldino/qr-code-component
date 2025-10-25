# Frontend Mentor - Solução do componente de QR Code

Esta é uma solução para o desafio [QR code component](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H) do Frontend Mentor.  
Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação construindo projetos reais.

## Sumário

- [Visão geral](#visão-geral)
  - [Captura de tela](#captura-de-tela)
  - [Links](#links)
- [Meu processo](#meu-processo)
  - [Construído com](#construído-com)
  - [O que aprendi](#o-que-aprendi)
  - [Desenvolvimento contínuo](#desenvolvimento-contínuo)
  - [Recursos úteis](#recursos-úteis)
- [Autor](#autor)

---

## Visão geral
O **QR Code Component** é um projeto desenvolvido a partir de um desafio do Frontend Mentor, com o objetivo de praticar os fundamentos de **HTML** e **CSS**.  
O foco principal foi construir um card centralizado, limpo e responsivo, contendo um **QR Code**, um título e uma breve descrição.  

Este projeto reforçou conceitos importantes como **alinhamento com Flexbox**, uso de **variáveis CSS** e boas práticas de **design minimalista**.

### Captura de tela

![](./images/Captura%20de%20tela%202025-10-25%20174342.png)

### Links

- **URL da solução:** [https://www.frontendmentor.io/solutions/qr-code-component](https://www.frontendmentor.io/solutions/qr-code-component)  
- **URL do site ao vivo:** [https://luizgaldino-qrcode.netlify.app](https://luizgaldino-qrcode.netlify.app)

---

## Meu processo

Durante o desenvolvimento deste projeto, comecei criando a estrutura HTML com foco na **semântica** e na **organização dos elementos**.  
Em seguida, apliquei os estilos com **CSS**, priorizando a simplicidade e o uso de **Flexbox** para centralizar o card na tela de forma responsiva.

Busquei manter o design o mais fiel possível ao layout original do desafio, ajustando espaçamentos, cores e tamanhos de fonte de acordo com o design proposto.  
Finalizei o projeto validando a aparência em diferentes tamanhos de tela para garantir uma boa **responsividade** e **experiência do usuário**.

### Construído com

- Marcação **HTML5 semântica**  
- **Propriedades personalizadas de CSS**  
- **Flexbox**  

---

### O que aprendi

Este foi um desafio simples, mas valioso para reforçar os fundamentos de **HTML e CSS**.  
Pratiquei o uso de **Flexbox** para centralizar o conteúdo vertical e horizontalmente, além de aprimorar meu entendimento sobre **design responsivo de cards**.

Aqui está um exemplo de como centralizei o card na tela:

```css
body {
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
  background-color: hsl(212, 45%, 89%);
}
