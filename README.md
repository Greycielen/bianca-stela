# Bianca Stela — Consultoria de Imagem

Landing page institucional com lista de espera. Site estático (HTML, CSS e JavaScript puros), sem dependências de build — pronto para publicar no GitHub Pages ou em qualquer hospedagem estática.

## Estrutura

```
bianca-stela-landing/
├── index.html              # A página (estilos e scripts embutidos)
├── assets/
│   ├── bianca-hero.png     # Retrato principal (topo)
│   ├── bianca-sobre.png    # Retrato — seção Sobre / Estratégia
│   ├── bianca-estilo.jpg   # Retrato — seção A consultoria
│   ├── monogram-esmeralda.svg
│   ├── monogram-ouro.svg
│   └── favicon.svg
└── README.md
```

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

## Trocar fotos

Substitua os arquivos em `assets/` mantendo os mesmos nomes. Recomendado: imagens em formato retrato (4:5 ou 3:4) com cerca de 1200–1600 px de largura, otimizadas para web.
