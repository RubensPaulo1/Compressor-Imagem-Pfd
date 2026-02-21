## Compressor de Arquivos (PDF e Imagem)

Aplicação para **comprimir arquivos PDF e imagens (JPG/PNG)**.  
Ideal para reduzir o tamanho de arquivos antes de enviar por e‑mail ou fazer upload.

### Funcionalidades

- **Comprimir PDF** — Ghostscript; gera arquivo com sufixo `_comprimido.pdf`.
- **Comprimir Imagens (JPG/PNG)** — Pillow (PIL); qualidade ajustável para JPG; sufixo `_comprimido.ext`.

---

### Requisitos

- **Python 3.x**
- **Pillow (PIL)** para imagens
- **Ghostscript** (apenas para PDF)
- **Node.js** (apenas para a GUI em React)

---

### Como rodar

1. **Backend (API)** — na pasta do projeto:
   ```bash
   pip install -r requirements.txt
   python api.py
   ```
   A API sobe em `http://localhost:5000`.

2. **Frontend** — em outro terminal:
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

3. Abra **http://localhost:3000** no navegador, escolha PDF ou imagem, ajuste a qualidade (para JPG) e clique em comprimir. O arquivo comprimido será baixado automaticamente. 


