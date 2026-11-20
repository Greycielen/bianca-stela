# Bianca Stela — Consultoria de Imagem

Landing page institucional com lista de espera. Site estático (HTML, CSS e JavaScript puros), sem dependências de build — pronto para publicar no GitHub Pages ou em qualquer hospedagem estática.

## Estrutura

```
bianca-stela-landing/
├── index.html              # A página (estilos e scripts embutidos)
├── privacidade.html        # Política de Privacidade (LGPD)
├── assets/
│   ├── bianca-hero.png     # Retrato principal (topo)
│   ├── bianca-estilo.jpg   # Retrato — seção A consultoria
│   ├── bianca-sobre.png    # Retrato — seção Estratégia
│   ├── bianca-sobre5.jpg   # Retrato — seção Sobre
│   ├── monogram-esmeralda.svg
│   ├── monogram-ouro.svg
│   ├── favicon.svg
│   ├── favicon-32.png
│   └── apple-touch-icon.png
└── README.md
```

> As imagens são publicadas **sem metadados (EXIF)** — número de série de câmera, datas e localização são removidos antes de versionar.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie estes arquivos (o `index.html` deve ficar na raiz do repositório).
2. No repositório, vá em **Settings → Pages**.
3. Em **Source**, escolha a branch `main` e a pasta `/ (root)`. Salve.
4. Em alguns minutos o site fica no ar em `https://<seu-usuario>.github.io/<nome-do-repo>/`.

## Formulário de lista de espera

O formulário usa o [Formspree](https://formspree.io). O endpoint já está configurado no `index.html`:

```
action="https://formspree.io/f/mzeenpgg"
```

- Cada inscrição chega no e-mail cadastrado no painel do Formspree e também fica organizada por lá.
- **Privacidade:** o endereço de e-mail de destino **não** aparece no código — o Formspree mantém o destino privado. Por isso o código pode ficar em repositório público sem expor e-mail pessoal.
- Campos enviados: nome, e-mail, WhatsApp (opcional), serviço de interesse e mensagem (opcional).
- Para trocar o destino, basta criar um novo formulário no Formspree e substituir o ID `mzeenpgg` no `action`.

## Política de Privacidade (LGPD)

O site tem uma página `privacidade.html`, com link no formulário e no rodapé. Ela descreve controlador, finalidade, base legal, o uso da Formspree (operador, nos EUA), retenção e os direitos do titular.

> **Ação pendente:** no item 08 há um marcador `[adicione aqui seu e-mail de contato]` — substitua por um e-mail de contato (idealmente comercial, não pessoal) para que o titular possa exercer seus direitos. Enquanto isso, os pedidos também podem chegar pelo próprio formulário do site.

## Trocar fotos

Substitua os arquivos em `assets/` mantendo os mesmos nomes. Recomendado: imagens em formato retrato (4:5 ou 3:4) com cerca de 1200–1600 px de largura, otimizadas para web.
