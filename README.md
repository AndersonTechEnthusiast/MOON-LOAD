# 🌙 MOON LOAD - Automatizador de Downloads e Transcrições

## 🚀 Sobre o Projeto
MOON LOAD é um script Python automatizado para o download de vídeos e áudios do YouTube, seguido da transcrição do áudio e geração de documentos em Word e PDF com as informações extraídas.

Ele inclui um sistema de carregamento visual 🌚 e permite a seleção interativa de diretórios e links.

---

## 🔧 Funcionalidades

✅ **Download de vídeos e áudios** do YouTube.

✅ **Transcrição do áudio** usando Whisper AI.

✅ **Criação de documentos Word e PDF** com os dados extraídos.

✅ **Organização de arquivos** em pastas automáticas.

✅ **Interface interativa** com feedback dinâmico.

---

## 📦 Dependências
Antes de executar, certifique-se de instalar as bibliotecas necessárias:
```sh
pip install pytubefix whisper reportlab python-docx validators requests
```

---

## ▶️ Como Usar
1. **Execute o script:**
   ```sh
   python index.py
   ```
2. **Informe o diretório de armazenamento.**
3. **Insira os links do YouTube.**
4. **O script baixará o vídeo, extrairá o áudio e criará os documentos automaticamente.**

---

## 📂 Estrutura dos Arquivos
```
📁 MoonLoad/
 ├── 📁 [Nome do Diretório]/
 │    ├── 🎥 video.mp4
 │    ├── 🎵 audio.mp3
 │    ├── 🖼️ thumbnail.jpg
 │
 ├── 📁 [Nome do Diretório]-Word/
 │    ├── 📄 transcricao.docx
 │
 ├── 📁 [Nome do Diretório]-PDF/
 │    ├── 📑 transcricao.pdf
```

---

## ✨ Créditos
Este projeto foi desenvolvido por **Anderson Pires**.
GitHub: [AndersonTechEnthusiast](https://github.com/AndersonTechEnthusiast)

🚀 Aproveite e contribua para melhorias! 😃


