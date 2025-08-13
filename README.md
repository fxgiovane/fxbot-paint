# FXBot Paint 🎯

<div align="center">

**▌ <a href="#status">STATUS</a> ▌ <a href="#pt-br">PT‑BR</a> ▌ <a href="#english">ENGLISH</a> ▌ <a href="#info">INFO</a> ▌**

</div>

---

## STATUS

<div align="center">

<img src="https://img.shields.io/badge/version-v7.2%20(API--free)-6a5acd?style=for-the-badge&labelColor=1b1b25">
<img src="https://img.shields.io/badge/status-active-2ecc71?style=for-the-badge&labelColor=1b1b25">
<img src="https://img.shields.io/badge/license-MIT-95a5a6?style=for-the-badge&labelColor=1b1b25">
<img src="https://img.shields.io/badge/language-JavaScript-f39c12?style=for-the-badge&labelColor=1b1b25&logo=javascript&logoColor=white">

</div>

- **Última atualização:** 2025‑08‑13  
- **API:** removida / indisponível (`401 Unauthorized`) — o bot funciona **100% via toast “Acabou a tinta”**  
- **Fluxo:** pinta sem dó → toast → commit → aguarda cooldown → retoma sozinho  
- **Execução rápida:** via **Bookmarklet** (`javascript:fetch(...)`) ou executando o `.js` no console  
- **Atenção:** o site‑alvo recebe **atualizações diárias** — quebras e ajustes são **normais**

---

## PT-BR

### 📌 Sobre
O **FXBot Paint** é uma ferramenta de **automação de cliques** para pintar pixels automaticamente.  
Não é hack, não explora falhas — apenas reproduz cliques que você faria manualmente.

> ⚠️ O site‑alvo tem **mudanças diárias**. Se algo quebrar, é esperado.

### 🚀 Como usar

#### Método rápido (Bookmarklet)
1. Crie um **favorito** no navegador.
2. No campo **URL** do favorito, cole o código abaixo:
   ```javascript
   javascript:fetch('https://raw.githubusercontent.com/fxgiovane/fxbot-paint/main/fxbot.js').then(r=>r.text()).then(eval)
   ```
3. Abra a página onde quer pintar e clique no favorito.

#### Método manual
1. Baixe ou copie o [`fxbot.js`](https://github.com/fxgiovane/fxbot-paint/blob/main/fxbot.js).  
2. Abra o **Console** (F12 → Aba “Console”), cole o conteúdo e pressione **Enter**.

### ⚙️ O que ele faz
- Pinta em alta velocidade até o site emitir o toast **“Acabou a tinta”**.  
- Ao detectar o toast: **pausa**, **faz commit**, **espera o cooldown** (padrão 10min) e **retoma sozinho**.  
- Interface **bilíngue PT‑BR/EN** (baseada no idioma do navegador).

### 🛠 Dicas
- Mantenha a paleta aberta quando for iniciar.
- Use **CPS** conforme o seu PC/sessão aguenta.
- Se pausou, pode **retomar** do ponto certo; se parar, zera.

### 📜 Licença e responsabilidade
- Licença **MIT** (veja o arquivo `LICENSE`).  
- Uso por **conta e risco do usuário**.  
- O autor **não se responsabiliza** por mau uso, bloqueios ou danos.

[🔼 Voltar ao topo](#fxbot-paint-)

---

## ENGLISH

### 📌 About
**FXBot Paint** is a **click automation** tool for auto‑painting pixels.  
It’s not hacking and doesn’t exploit vulnerabilities — it only automates your normal clicks.

> ⚠️ The target site changes **daily**. Breakages are expected.

### 🚀 How to use

#### Quick method (Bookmarklet)
1. Create a **bookmark** in your browser.
2. In the bookmark **URL**, paste:
   ```javascript
   javascript:fetch('https://raw.githubusercontent.com/fxgiovane/fxbot-paint/main/fxbot.js').then(r=>r.text()).then(eval)
   ```
3. Open the target page and click the bookmark.

#### Manual method
1. Download or copy [`fxbot.js`](https://github.com/fxgiovane/fxbot-paint/blob/main/fxbot.js).  
2. Open the **Console** (F12 → “Console” tab), paste the code and hit **Enter**.

### ⚙️ What it does
- Paints at high speed until the site shows the **“Out of ink”** toast.  
- On toast detection: **pause**, **commit**, **wait cooldown** (default 10min), **resume automatically**.  
- **Bilingual UI PT‑BR/EN** (based on browser locale).

### 🛠 Tips
- Keep the palette open before starting.
- Tune **CPS** to match your device/session.  
- Pause lets you **resume**; Stop **resets** everything.

### 📜 License & responsibility
- **MIT** license (see `LICENSE`).  
- Use at your **own risk**.  
- The author is **not responsible** for misuse, bans or damages.

[🔼 Back to top](#fxbot-paint-)

---

## INFO

- **Repo:** https://github.com/fxgiovane/fxbot-paint  
- **Main script:** `fxbot.js`  
- **Execution:** Bookmarklet or Console (no external API required)  
- **Engine:** toast‑driven ink control (commit → cooldown → resume)  
- **Theme:** dark, minimal, neon accents  
- **Contrib:** PRs e issues são bem‑vindos (relate o passo a passo para reproduzir)  

> **Nota de compatibilidade:** extensões de bloqueio de scripts/ads podem interferir; se algo não iniciar, tente desativá‑las na página‑alvo.

[🔼 Back to top](#fxbot-paint-)
