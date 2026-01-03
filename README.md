
```markdown
# Agência Criativa Web 

Um site moderno e responsivo para a **Agência Criativa Web**, desenvolvido com **HTML5**, **CSS3** e agora refatorado com **Sass**, aplicando conceitos de **Design Responsivo**, **Unidades Relativas**, **Flexbox**, **CSS Grid** e a metodologia **BEM** para nomenclatura de classes.  
O projeto demonstra boas práticas de semântica, acessibilidade, modularização e adaptação para diferentes tamanhos de tela.

---

## 🚀 Funcionalidades

- **Layout responsivo**: adaptável para desktop, tablet e mobile.
- **Menu de navegação**:
  - Alinhado com Flexbox.
  - Versão responsiva com hambúrguer menu para telas menores.
  - Cabeçalho fixo no topo, com altura controlada e sem sobrepor o conteúdo.
- **Seções principais**:
  - **Home (`.hero`)**: banner de boas-vindas com destaque para o diferencial da agência.
  - **Sobre Nós (`.sobre`)**: descrição da agência e seus valores.
  - **Serviços (`.servicos`)**: estruturados em **CSS Grid** para um layout flexível.
  - **Depoimentos (`.depoimentos`)**: comentários fictícios de clientes.
  - **Contato (`.contato`)**: informações de contato e formulário acessível.
- **Formulário de contato (`.form-contato`)**:
  - Campos para nome, e-mail e mensagem.
  - Labels e atributos `required` para acessibilidade.
- **Imagens responsivas**:
  - Ajustadas com `max-width: 100%` e `height: auto`.
  - Limite de altura aplicado para evitar imagens muito grandes.
  - Adaptadas via media queries para diferentes tamanhos de tela.
- **Unidades relativas** (`rem`, `em`, `%`, `vh`, `vw`, `fr`) para garantir flexibilidade.
- **Media queries** para adaptação em diferentes resoluções.
- **Nomenclatura BEM** para organização e manutenção do CSS.

---

## 🛠️ Tecnologias utilizadas

- **HTML5**: estrutura semântica e acessível.
- **CSS3/Sass**:
  - Flexbox para alinhamento.
  - CSS Grid para layout dos serviços.
  - Variáveis Sass para cores e espaçamentos.
  - Media queries para responsividade.
  - Metodologia **BEM** para organização e manutenção do CSS.
- **Google Fonts**: tipografia moderna (Inter).
- **JavaScript simples**: atualização automática do ano no rodapé.

---

## 📂 Estrutura do projeto

```
/
├── index.html        # Página principal (HTML5 semântico e acessível)
├── estilos.css       # Estilos externos (compilados do Sass)
├── /sass             # Pasta com partials Sass
│   ├── _variaveis.scss
│   ├── _mixins.scss
│   ├── _layout.scss
│   ├── _componentes.scss
│   └── estilos.scss  # Arquivo principal que importa todos os partials
└── README.md         # Documentação do projeto
```

---

## 🎨 Identidade visual

- **Paleta de cores**:
  - Fundo escuro moderno (`#0b0f14`, `#111720`).
  - Azul primário (`#4f7dfd`) e verde acento (`#7af0c3`).
  - Texto claro (`#eaf0ff`) e secundário (`#b8c3da`).
- **Tipografia**: [Inter](https://fonts.google.com/specimen/Inter), limpa e profissional.
- **Estilo**: moderno, minimalista e com foco em acessibilidade.
- **Logo**: atualmente apenas texto estilizado, sem imagem.

---

## 📱 Responsividade

- Layout adaptado com **media queries**:
  - Até **1024px**: ajustes em grids e hero.
  - Até **768px**: menu hambúrguer, grids empilhados.
- Imagens otimizadas com `srcset`, `sizes` e limites de altura.
- Uso de unidades relativas para escalabilidade.

---

## 🧩 Acessibilidade

- Uso de elementos semânticos (`header`, `main`, `section`, `nav`, `footer`).
- Labels associados a inputs.
- `aria-label`, `aria-labelledby` e `aria-describedby` para navegação assistiva.
- Link de **skip to content** para leitores de tela.
- Foco visível em elementos interativos.

---

## 📖 Como executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/Li-code1/agenciaCriativaWeb.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd agencia-criativa-web
   ```
3. Abra o arquivo `index.html` em qualquer navegador moderno.

---

## 📌 Melhorias futuras

- Implementar envio real do formulário com backend (Node.js, PHP ou outro).
- Adicionar seção de portfólio com projetos interativos.
- Criar animações leves com CSS para transições.
- Expandir uso de **BEM** em novos componentes (ex.: portfólio, blog).

---

## 📄 Licença

Este projeto é de uso livre para fins educacionais e demonstração.  
Sinta-se à vontade para adaptar e evoluir conforme suas necessidades.

---
```

---
