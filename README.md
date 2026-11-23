# Júnior Barros — Web Portfolio

Portfólio estático, responsivo e trilíngue (ES/PT/EN) para GitHub Pages.

## Arquivos
- `index.html` — conteúdo e estrutura.
- `styles.css` — design e responsividade.
- `script.js` — traduções, menu e contato.
- `assets/` — ícone e imagem social SVG.
- `.nojekyll` — impede processamento Jekyll desnecessário.

## Publicar no GitHub Pages
1. Crie um repositório público chamado `98nom4d.github.io` no GitHub da conta `98nom4d` (ou use outro nome).
2. Envie **todos os arquivos e a pasta `assets` para a raiz** do repositório. Não envie apenas o arquivo ZIP.
3. Abra **Settings → Pages → Build and deployment**.
4. Selecione **Deploy from a branch → main → /(root) → Save**.
5. Se o repositório for `98nom4d.github.io`, o endereço será `https://98nom4d.github.io/`. Se usar `portfolio-web`, o endereço será `https://98nom4d.github.io/portfolio-web/`.

## Personalizar antes de publicar
- **E-mail:** em `script.js`, procure `const recipient=''` e preencha com seu endereço profissional. Sem isso, o formulário abre o e-mail **sem destinatário**.
- **GitHub:** os links apontam para `github.com/98nom4d`.
- **LinkedIn:** o link aponta para `linkedin.com/in/juniorbarros98/`; confirme o endereço.
- **Projetos:** os mockups são ilustrações criadas em HTML/CSS, não screenshots nem demos. Substitua os detalhes e acrescente URLs reais quando estiverem publicados.
- **Marca:** é um portfólio pessoal com o nome Júnior Barros, independente da Avansav.
- **Fontes:** utiliza Google Fonts. Se a rede estiver indisponível, usa fontes locais substitutas.
- **Contato:** o formulário é 100% client-side, sem armazenamento. Precisa de um aplicativo de e-mail configurado no dispositivo do visitante. Para receber mensagens diretamente pelo site, será necessário integrar um serviço externo.

## Rodar localmente
Abra `index.html` no navegador ou, com Python instalado, execute:

```bash
python -m http.server 8000
```

Depois acesse `http://localhost:8000`.

## Compatibilidade
HTML, CSS, JavaScript puro. Sem build, Node, API, servidor ou banco. Compatível com GitHub Pages.

## Contato por WhatsApp

Os botões de contato abrem o WhatsApp de `+34 653 819 815`, com mensagem inicial no idioma selecionado. Altere `whatsappMessages` e o número `34653819815` em `script.js` para personalizar.

## Imagens dos projetos

As capas são tipográficas e não simulam telas reais. Para usar imagens de projetos reais, substitua o conteúdo dos blocos `.project-art` em `index.html` por elementos `<img>` com capturas suas e configure o CSS correspondente.


## Ajuste do favicon e logo
- Os ícones em `assets/favicon.ico`, `assets/favicon.png` e `assets/apple-touch-icon.png` usam a logo JB enviada.
- Clicar na logo da barra superior leva diretamente ao início da página, sem rolagem suave.
- Se o ícone antigo persistir na aba, atualize com Ctrl+F5 e feche/abra a aba.
