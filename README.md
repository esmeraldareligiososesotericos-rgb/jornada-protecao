# Jornada de Proteção — site

Página da aula do Kit Jornada de Proteção (Loja Esmeralda). Um único arquivo `index.html`, pronto pra publicar no GitHub Pages.

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (pode ser público ou privado, mas o GitHub Pages gratuito só publica repositórios públicos).
2. Suba o arquivo `index.html` desta pasta para a raiz do repositório (arrastar e soltar pela interface do GitHub funciona).
3. No repositório, vá em **Settings → Pages**.
4. Em "Build and deployment", escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)`. Salve.
5. Espere 1 ou 2 minutos — o GitHub mostra o link do site no topo da mesma página (algo como `https://seu-usuario.github.io/nome-do-repositorio/`).

## Trocar o vídeo depois

Quando gravar a aula de verdade e subir no YouTube (não listado), abra o `index.html` num editor de texto, procure por:

```
src="https://www.youtube-nocookie.com/embed/MReXCd6B84k"
```

e troque `D3TUvhyHPxU` pelo ID do vídeo novo (o trecho depois de `v=` no link do YouTube). Troque também o link de "assistir no YouTube" logo abaixo, com o mesmo ID.

## Domínio próprio (opcional)

Se um dia quiser usar um domínio da loja em vez do endereço `github.io`, é só criar um arquivo `CNAME` na raiz do repositório com o domínio dentro, e apontar o DNS desse domínio para o GitHub Pages (a própria tela de Settings → Pages explica o passo).
