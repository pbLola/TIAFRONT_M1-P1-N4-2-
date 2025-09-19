# TIA_FRONTEND_M1_P1_N3 — Página de Notícia (Nível 3)

![Print do Projeto](assets/images/preview.png)

## Descrição do projeto

Página de notícia construída para o **Módulo 1 (Fundamentos)**.  
Projeto P1 Nível 3 foca em **HTML semântico**, organização de arquivos, imagens acessíveis, tabelas simples e **SEO básico**.

## Funcionalidades desejadas

- Estrutura semântica completa (`header`, `main`, `article`, `aside`, `footer`).
- Imagens em `<figure>` com `<figcaption>` e `alt` descritivo.
- Tabela simples com `<caption>`, `<thead>`, `<tbody>`.
- Links internos e externos com `rel="noopener noreferrer"` onde aplicável.
- Microinterações CSS: hover para links, imagens e botões.
- Compartilhamento via Web Share API com fallback para clipboard.

## ⚙️ Tecnologias usadas

- **HTML5** (semântica, acessibilidade)
- **CSS3** (grid/flex, variáveis customizadas, sombras neumorphic)
- **JavaScript** (vanilla — Web Share API + fallback)
- **Google Fonts**: Poppins

## 💡 Funcionalidades implementadas

- Header fixo com navegação.
- Article principal com `figure` e `figcaption`.
- Tabela de estatísticas com `caption`.
- Aside com posts relacionados e box da autora.
- Botão de compartilhar com Web Share API / Clipboard fallback.
- Microinterações CSS seguindo estilo neumorphic.

## 🔧 Melhorias aplicadas após feedback

- Atualizada imagem principal para ter `loading="lazy"`.
- Ajustes de `:focus` para melhorar navegação por teclado.

## 🚀 Próximos passos

- Adicionar testes de contraste automatizados (axe-core) e correções.
- Implementar animação leve de entrada (fade-in) no carregamento.
- Substituir imagens placeholder por assets finais com compressão (WebP).
