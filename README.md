# 🚀 Máquina ISP — Apresentação Comercial Interativa

Apresentação comercial interativa desenvolvida em HTML/CSS/JS puro, sem dependências de build.

---

## 📁 Estrutura do Projeto

```
/
├── index.html                  ← Apresentação principal (arquivo de entrada)
├── index_v4.html               ← Versão de backup/rascunho (não publicada)
├── patch_slide3.py             ← Script utilitário de patch (desenvolvimento)
├── .gitignore                  ← Arquivos ignorados pelo Git
│
├── images/                     ← Imagens e assets visuais
│   ├── Logo Principal - Versão Branco - Azul.png
│   ├── Imagem capa máquina isp.png
│   ├── Imagem final da apresentação.png
│   ├── GABI.png / LIA 1.png / NOAH.png / TEO.png
│   ├── dashboard-tela1.png.png / tela2 / tela3
│   └── logos dos parceiros (hubsoft, ixc, sgp, etc.)
│
├── videos/                     ← Vídeos dos agentes (MP4)
│   ├── Vídeo LIA.mp4
│   ├── Vídeo NOAH.mp4
│   ├── Vídeo TEO.mp4
│   └── Vídeo gabi - entrando em cena.mp4
│
├── css/                        ← (reservado para estilos externos futuros)
├── javascript/                 ← (reservado para scripts externos futuros)
│
├── maquina-isp-mockup/         ← Mockup do sistema/dashboard
│   ├── desktop/
│   │   ├── index.html
│   │   ├── styles.css
│   │   └── app.js
│   └── mobile/
│
├── Design System Máquina ISP/  ← Guia visual e assets de identidade
│   └── artools/
│
└── Design System Thundera/     ← Design system legado / referência
```

---

## ▶️ Como Executar

Abra o arquivo `index.html` diretamente no navegador.

> **Recomendado:** Use uma extensão como **Live Server** (VS Code) para evitar restrições de CORS ao carregar vídeos e imagens localmente.

---

## 🛠️ Tecnologias

- HTML5 / CSS3 / JavaScript (Vanilla)
- GSAP (animações)
- Google Fonts (Inter, JetBrains Mono)

---

## ⚠️ Observações

- Os vídeos dos agentes (`.mp4`) estão na pasta `videos/`. Certifique-se de que estão presentes para o funcionamento correto.
- O arquivo `index_v4.html` é uma versão de desenvolvimento e **não deve ser publicado**.
