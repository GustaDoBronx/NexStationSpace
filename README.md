# NexStationSpace
# 🛰️ NexStation

Site responsivo de uma estação espacial comercial fictícia, criado com **HTML, CSS e JavaScript puro**, sem frameworks e sem etapa de build.

> Projeto de demonstração. A NexStation não existe, mas a órbita é bonita.

## ✨ Funcionalidades

- Layout responsivo, de celular a desktop
- Fundo de estrelas animado em `<canvas>`
- Estação orbitando a Terra em SVG animado
- Painel de telemetria com altitude, velocidade e órbitas do dia
- Linha do tempo da missão
- Formulário de lista de espera com validação de e-mail
- Menu mobile acessível
- Respeita `prefers-reduced-motion` e tem foco visível no teclado

## 🚀 Como rodar

Não precisa instalar nada. Clone o repositório e abra o arquivo no navegador:

```bash
git clone https://github.com/SEU-USUARIO/nexstation.git
cd nexstation
# abra o index.html no navegador, ou use um servidor local:
python3 -m http.server 8000
```

Depois acesse `http://localhost:8000`.

## 🌐 Publicar no GitHub Pages

1. Envie os arquivos para o repositório.
2. Vá em **Settings → Pages**.
3. Em **Source**, escolha **Deploy from a branch**, selecione `main` e a pasta `/ (root)`.
4. Salve. Em alguns minutos o site estará em `https://SEU-USUARIO.github.io/nexstation/`.

## 📁 Estrutura

```
nexstation/
├── index.html   # estrutura da página e JavaScript
├── style.css    # estilos
└── README.md
```

## 🎨 Personalização

As cores e fontes ficam nas variáveis CSS no início do `style.css`:

```css
:root {
  --void: #0b1022;   /* fundo */
  --solar: #ffb04a;  /* destaque */
  --plasma: #6f8cff; /* azul orbital */
}
```

## 🛠️ Tecnologias

- HTML5 semântico
- CSS3 (Grid, Flexbox, variáveis, media queries)
- JavaScript (Canvas API)
- Fontes: [Unbounded](https://fonts.google.com/specimen/Unbounded) e [Figtree](https://fonts.google.com/specimen/Figtree) via Google Fonts

## 📄 Licença

Distribuído sob a licença MIT. Use, modifique e compartilhe à vontade.
