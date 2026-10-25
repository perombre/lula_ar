# Lula em AR

Página web que mostra o personagem em 3D e em realidade aumentada, sem instalar nada.

- **Android:** abre no Chrome → "Ver na minha sala (AR)" usa o AR do Google (WebXR / Scene Viewer).
- **iPhone:** abre no Safari → usa o AR Quick Look com `lula_danca.usdz`.

## Arquivos

| Arquivo | Conteúdo |
|---|---|
| `index.html` | Página com `<model-viewer>` e os botões Parado / Dança / Aceno |
| `lula.glb` | Modelo para web e Android (malha com Draco, texturas JPEG, 3 animações) |
| `lula_danca.usdz` | Modelo para iPhone (animação de dança) |

## Publicação no Cloudflare Pages

Site estático, sem etapa de build:

- **Framework preset:** None
- **Build command:** (vazio)
- **Build output directory:** `/`

Cada `git push` na branch `main` atualiza o site automaticamente.
