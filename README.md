[README.md](https://github.com/user-attachments/files/24694665/README.md)
# Ferramentaria Elétrica CA (Static)

Este projeto é **100% estático** (HTML único) e pode ser publicado no **GitHub Pages** ou **Vercel**.

## Como rodar localmente

> Dica: o leitor de QR precisa de **HTTPS** (ou `localhost`).

```bash
python -m http.server 8080
# abra http://localhost:8080
```

## Deploy no GitHub Pages

1. Suba estes arquivos para um repositório.
2. Em **Settings → Pages**:
   - Source: **Deploy from a branch**
   - Branch: **main** / folder **/** (root)
3. Acesse a URL que o GitHub Pages mostrar.

## Deploy na Vercel

1. Importe o repositório na Vercel.
2. Framework Preset: **Other**
3. Build Command: *(deixe vazio)*
4. Output Directory: *(deixe vazio)*

## Observações importantes

- **Dados ficam no navegador** (LocalStorage + IndexedDB). Cada dispositivo/navegador tem sua própria base.
- Para zerar dados: limpe o armazenamento do site no navegador.
- O Service Worker (`sw.js`) faz cache leve para abrir mais rápido e funcionar melhor com conexão instável.

