# Terra–Lua: Medidor Diário (PWA) — GitHub Pages

Este pacote está pronto para publicar no **GitHub Pages**.

## Passo a passo

1. Crie um repositório novo no GitHub (por exemplo, `terra-lua`).
2. Envie **estes arquivos** para a raiz do repositório:
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
   - `404.html`
3. No GitHub, vá em **Settings → Pages**.
4. Em **Source**, escolha **Deploy from a branch**.
5. Selecione a branch **main** e a pasta **/** (root). Clique **Save**.
6. Aguarde o Pages gerar o site. O link ficará algo como:
   `https://SEU_USUARIO.github.io/terra-lua/`
7. Abra o link no celular (Chrome/Android), toque no menu (⋮) e escolha **Adicionar à tela inicial**.

> Dica: O `start_url` e `scope` já estão relativos (`"./"`), então funcionam
> corretamente tanto em `https://SEU_USUARIO.github.io/terra-lua/` quanto em uma raiz.

## Desenvolvimento local (opcional)

Se quiser testar antes:
```bash
python -m http.server 8000
# depois acesse em http://localhost:8000
```

Pronto! Seu medidor Terra–Lua vira um app instalável e offline.
