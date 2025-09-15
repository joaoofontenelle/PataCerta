# Copilot Instructions for Pata Certa

## Visão Geral
Este projeto é uma plataforma web para adoção responsável de animais, conexão entre ONGs, voluntários e adotantes, e educação sobre cuidados com pets. O código é majoritariamente HTML, CSS e JavaScript, hospedado no GitHub Pages.

## Estrutura do Projeto
- **Páginas HTML**: Cada funcionalidade principal tem sua própria página (`index.html`, `adotepets.html`, `sobrenos.html`, etc.).
- **Estilos**: Centralizados em `styles/style.css`. Use variáveis CSS e classes já existentes para manter consistência visual.
- **Imagens e SVGs**: Guardados em `assets/`. Referencie sempre por caminhos relativos.
- **Scripts JS**: (Em desenvolvimento) Devem ser adicionados em arquivos separados e referenciados nas páginas conforme necessário.

## Convenções e Padrões
- **Sem frameworks**: Não utilize React, Vue, Angular ou similares. Apenas HTML/CSS/JS puro.
- **Responsividade**: Use media queries e classes utilitárias do CSS para garantir boa experiência em dispositivos móveis.
- **Nomenclatura**: Siga o padrão de nomes já existente para IDs, classes e arquivos. Exemplo: `#banner`, `.adotar`, `#conteudo`.
- **Acessibilidade**: Priorize textos alternativos em imagens e navegação clara.

## Fluxos de Trabalho
- **Deploy**: O site é publicado via GitHub Pages. Não há processo de build; basta atualizar os arquivos no repositório.
- **Testes**: Não há testes automatizados. Valide visualmente as páginas e funcionalidades.
- **Debug**: Use o console do navegador para depurar JS. Para CSS, utilize as ferramentas de inspeção do navegador.

## Integrações e Dependências
- **Fontes**: Importadas via Google Fonts no CSS.
- **Sem dependências externas JS**: Evite bibliotecas JS externas, exceto se absolutamente necessário e aprovado.

## Exemplos de Padrões
- Para adicionar um novo botão estilizado:
  ```html
  <a class="adotar" href="#">Adotar</a>
  ```
- Para criar uma nova seção responsiva:
  ```css
  @media (max-width: 600px) {
    .colunasrodape { flex-direction: column; }
  }
  ```

## Arquivos-Chave
- `index.html`, `adotepets.html`, `sobrenos.html`, etc.: Estrutura das páginas
- `styles/style.css`: Estilos globais e variáveis
- `assets/`: Imagens e ícones

## Recomendações para Agentes
- Mantenha o padrão visual e estrutural existente.
- Documente mudanças relevantes no README.
- Priorize clareza, acessibilidade e responsividade.

---
Se algo estiver pouco claro ou faltar contexto, peça feedback ao usuário antes de avançar.
