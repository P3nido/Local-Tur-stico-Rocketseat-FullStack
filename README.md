# 🌍 Local Turístico - Landing Page

Este é um projeto de uma Landing Page de turismo desenvolvido como um desafio prático da formação **Rocketseat**. O foco principal foi a aplicação de fundamentos de HTML semântico e estilização avançada com CSS.

## 🚀 Sobre o Desafio
O objetivo foi construir uma página de apresentação de um destino turístico, garantindo uma estrutura organizada e um layout visualmente atraente, seguindo fielmente o design proposto no Figma.

### ✨ Principais funcionalidades e requisitos:
- **Estrutura Semântica:** Uso de tags como `<header>`, `<section>`, `<main>` e `<footer>`.
- **Layout Responsivo:** Ajuste de imagens e containers para diferentes visualizações.
- **Estilização Detalhada:** - Uso de `border-radius` para imagens arredondadas.
  - Implementação de divisores personalizados (`divider`).
  - Manipulação de tipografia com `font-weight`, `text-transform` e `font-style`.
  - Ajuste de proporção de imagens com `object-fit: cover`.
  - Customização de marcadores de lista usando o pseudo-elemento `::marker`.

## 🛠️ Tecnologias Utilizadas
- **HTML5:** Para a estruturação semântica do conteúdo.
- **CSS3:** Para definição de cores, fontes, espaçamentos (margin/padding) e alinhamentos.
- **Figma:** Utilizado como base para o guia de estilo e layout.

## 📸 Estrutura da Página
A página está organizada da seguinte forma:
1. **Header:** Título principal com o nome do local em destaque.
2. **Introdução:** Chamada atrativa e parágrafo descritivo.
3. **Destaque:** Imagem principal com bordas arredondadas e legenda.
4. **Atrações:** Seção "Destinos Imperdíveis" com detalhes sobre 3 pontos turísticos específicos.
5. **Footer:** Rodapé centralizado com informações institucionais.

## 🎨 Destaques Técnicos
Durante o desenvolvimento, foram aplicadas técnicas para evitar distorção de imagens e garantir a hierarquia visual:
```css
/* Exemplo de solução aplicada para imagens */
img {
  width: 100%;
  height: 375px;
  object-fit: cover;
  border-radius: 28px;
}
