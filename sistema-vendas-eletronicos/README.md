# 📺 Solução TV Box — Landing Page de Vendas

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Responsivo](https://img.shields.io/badge/Responsivo-100%25-2ea44f)
![Acessibilidade](https://img.shields.io/badge/Acessibilidade-WCAG_AA-00A8E1)
![Dependências](https://img.shields.io/badge/Depend%C3%AAncias-0-success)
![Feito com IA](https://img.shields.io/badge/Desenvolvido_com-Claude_AI-D97757)
![Licença](https://img.shields.io/badge/Licen%C3%A7a-MIT-blue)

> **Landing page de vendas de página única** para uma loja de TV Box, com foco em conversão por WhatsApp. Projetada e implementada ponta a ponta com um **workflow moderno assistido por Inteligência Artificial** — do conceito e UX ao código final.

🔗 **Demo ao vivo:** `https://SEU-USUARIO.github.io/sistema-vendas-eletronicos` *(publique no GitHub Pages — veja [as instruções](#️-publicar-no-github-pages))*

![Prévia do site](screenshots/hero.png)

---

## 📋 Sobre o projeto

Site de vendas real para um negócio local de TV Box (aparelho que transforma qualquer televisão com HDMI em uma Smart TV). O objetivo central é **conversão**: levar o visitante do primeiro contato até uma conversa no WhatsApp, que é o principal canal de vendas do varejo brasileiro.

É um site **estático, sem framework e sem etapa de build** — carrega instantaneamente, roda em qualquer navegador e pode ser hospedado em qualquer lugar (GitHub Pages, Netlify, Vercel, uma hospedagem simples...). Toda a identidade visual gira em torno de um tema escuro "cinema", que remete à experiência de assistir a algo no sofá à noite.

**O que o site entrega:**

- Herói com proposta de valor clara e ilustração em SVG de uma TV "ligando"
- Três modelos de produto com **tabela comparativa** lado a lado
- Passo a passo de instalação em 3 etapas
- Vitrine de aplicativos compatíveis
- Seção de **assistência técnica** (segunda fonte de receita)
- Prova social (depoimentos) e **FAQ** em acordeão
- Chamadas para ação de WhatsApp com mensagem pré-preenchida, em pontos estratégicos

---

## 🧠 Desenvolvimento assistido por IA

Este projeto foi concebido e construído com um **fluxo de trabalho aumentado por IA** (usando o Claude, da Anthropic) — e isso é intencional. Saber dirigir uma IA para transformar uma ideia de negócio em um produto pronto para produção é uma das competências mais valorizadas no mercado atual.

Na prática, o desenvolvimento envolveu:

- **Traduzir requisitos de negócio em produto** — definir público, objetivo (conversão via WhatsApp), estrutura de seções e hierarquia da informação.
- **Iterar sobre design, texto e UX** por meio de prompts — ajustar layout, paleta, tom das mensagens e organização até chegar no resultado desejado.
- **Dirigir e revisar criticamente a saída** — decidir o que entra, o que sai e por quê, em vez de aceitar tudo cegamente.
- **Tomar decisões técnicas** — acessibilidade, responsividade, performance e contraste de cores (verificado no padrão WCAG AA).
- **Entregar e publicar** — organizar o projeto em um repositório limpo, pronto para deploy.

> Em resumo: este repositório demonstra o ciclo completo de **levar um produto do zero ao ar com IA como ferramenta de engenharia**.

---

## ✨ Funcionalidades

- 🎨 **Sistema de design em CSS Custom Properties** — tokens de cor, raio e espaçamento centralizados; trocar a marca inteira é questão de poucas variáveis.
- 📱 **Totalmente responsivo** — abordagem mobile-first com CSS Grid + Flexbox, adaptando-se a celular, tablet e desktop.
- ♿ **Acessível** — HTML semântico, foco visível por teclado (`:focus-visible`), respeito a `prefers-reduced-motion` e contraste no padrão **WCAG AA**.
- ⚡ **Zero dependências e zero build** — apenas HTML + CSS. Sem framework, sem bundler, sem JavaScript de runtime.
- 🖼️ **Ilustração do herói em SVG inline** — sem imagens externas, nada para carregar.
- 📊 **Tabela comparativa** de modelos.
- ❓ **FAQ em acordeão nativo** — `<details>`/`<summary>`, acessível e sem uma linha de JS.
- 💬 **Integração com WhatsApp** — links `wa.me` com mensagem pré-preenchida para cada contexto.
- 🖨️ **Pronto para exportar em PDF** — layout que se comporta bem na impressão.

---

## 🛠️ Tecnologias

| Camada | Tecnologia |
|---|---|
| Estrutura | HTML5 semântico |
| Estilo | CSS3 — Custom Properties, Grid, Flexbox, `clamp()`, media queries |
| Gráficos | SVG inline |
| Tipografia | Google Fonts (Bricolage Grotesque + Inter) |
| Dependências | **Nenhuma** — sem frameworks, sem build |

---

## 🏗️ Decisões técnicas

- **Estático primeiro:** sem toolchain nem passo de build, o site carrega de imediato e pode ser hospedado em qualquer serviço — inclusive de graça.
- **Design tokens com `--custom-properties`:** cores, raios e espaçamentos ficam em um único lugar, facilitando temas e re-branding.
- **Responsividade mobile-first:** Grid e Flexbox reorganizam o conteúdo em cada breakpoint sem duplicar marcação.
- **Acessibilidade de base:** landmarks semânticos, foco de teclado visível, animações que respeitam `prefers-reduced-motion` e contraste validado em WCAG AA.
- **Performance:** sem JavaScript de runtime, SVG embutido e uma pilha de fontes com *fallback* de sistema.
- **Progressive enhancement:** o FAQ usa `<details>` nativo — funciona mesmo sem JS.

### Estrutura do projeto

```
sistema-vendas-eletronicos/
├── index.html        # estrutura e conteúdo
├── styles.css        # estilos: design tokens, layout e responsividade
├── screenshots/      # imagens usadas neste README
├── LICENSE
└── README.md
```

---

## 🚀 Como rodar localmente

```bash
# Opção 1 — abrir direto
# basta abrir index.html no navegador

# Opção 2 — servidor local (recomendado)
python3 -m http.server 8000
# acesse http://localhost:8000
```

## ☁️ Publicar no GitHub Pages

1. Suba este repositório para o seu GitHub.
2. Vá em **Settings → Pages**.
3. Em **Branch**, selecione `main` e a pasta `/ (root)` → **Save**.
4. Em cerca de 1 minuto o site estará no ar em `https://SEU-USUARIO.github.io/sistema-vendas-eletronicos`.

---

## 🖼️ Mais telas

| Modelos e comparativo | Apps, passo a passo e assistência |
|:---:|:---:|
| ![Modelos](screenshots/modelos.png) | ![Recursos](screenshots/recursos.png) |

---

## 📝 Observações

- Os dados de contato (WhatsApp, CNPJ) presentes no código são **de demonstração**. Para uso real, basta editá-los em `index.html`.
- As marcas de terceiros citadas (Netflix, HBO/Max, ESPN, Disney+, entre outras) pertencem aos seus respectivos donos e aparecem apenas para indicar **compatibilidade de aplicativos**. A TV Box é um aparelho para acesso a serviços e conteúdos legalmente disponíveis.

---

## 👤 Autor

- **Nome:** [Seu Nome]
- **LinkedIn:** [seu-linkedin](https://linkedin.com/in/seu-usuario)
- **GitHub:** [@seu-usuario](https://github.com/seu-usuario)

## 📄 Licença

Distribuído sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
