
# Projeto de estudo - Formulario de convite
Projeto de um formulário para criação de um convite personalizado

## ✨ Sobre o Projeto

Este projeto é um projeto de estudo de um formulário completo de criação de um convite, dividido em seções claras. Objetivo princial do projeto foi desenvolver e aprender as varias formas de se usar un input

- con radio 
- com switch
- input sendo todo o conteúdo
- padronizacao de input em grid
- toggle button

O layout é baseado no projeto disponibilizado pela Rocketseat.

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica do conteúdo
- **CSS3** (puro): Estilização moderna com `grid layout`, `flexbox` e `:has()` para interações avançadas
- **Google Fonts**: importaçãao de tipograficas
- **SVG Icons**: Ícones vetoriais para tornar a experiência mais visual
- **Validações básicas**: Campos obrigatórios e feedback visual de erro

## 🎨 Layout

O projeto conta com dois painéis principais:
- **Aside**: Banner fixo com imagem ilustrativa 
- **Formulário**: Área de preenchimento com rolagem


A estrutura é feita com `grid`:
```css
#app {
  display: grid;
  grid-template-columns: 51.25% 48.75%;
  height: 100vh;
}
```
---

⚠️ Dificultades
- **switch button:** dificultade em fazer a palavra aparecer e mudar de acordo com a status do button
