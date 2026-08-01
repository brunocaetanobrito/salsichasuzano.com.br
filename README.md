# 🐾 Salsicha Suzano

> Landing page para divulgação de filhotes de Dachshund (Teckel) em Suzano/SP — feita para encantar, educar e conectar famílias responsáveis com o filhote certo.

[![Website](https://img.shields.io/badge/site-online-25D366?style=flat-square&logo=googlechrome&logoColor=white)](https://salsichasuzano.com.br)
[![License: MIT](https://img.shields.io/badge/license-MIT-8B4E26?style=flat-square)](LICENSE)
[![Made with](https://img.shields.io/badge/feito%20com-HTML%20%2B%20CSS%20%2B%20JS-C98A4B?style=flat-square)](index.html)
[![Stars](https://img.shields.io/github/stars/<seu-usuario>/salsichasuzano.com.br?style=flat-square&color=E8B56B&label=%E2%AD%90%20stars)](../../stargazers)

<p align="center">
  <a href="https://salsichasuzano.com.br"><strong>🌐 Acesse o site: salsichasuzano.com.br</strong></a>
</p>

<p align="center">
  <a href="../../stargazers">
    <strong>⭐ Curtiu o projeto? Deixa uma estrelinha aqui em cima — é de graça e ajuda muito! ⭐</strong>
  </a>
</p>

---

## 🐶 Sobre o projeto

Um site **single-page**, 100% estático (sem frameworks, sem build step — é abrir e usar), criado para apresentar uma ninhada de filhotes de Dachshund com pedigree, localizada em Suzano/SP, com entrega gratuita para o Alto Tietê.

Mais do que uma "vitrine de cachorrinho fofo", o site tem uma pegada de **adoção responsável**: antes de liberar o contato, o visitante passa por uma seção de conscientização sobre a raça e por um **quiz de compatibilidade**, pensado para filtrar famílias realmente preparadas para o compromisso de mais de uma década que é ter um Dachshund.

## ✨ Funcionalidades

- 🧩 **Quiz de compatibilidade** — 6 perguntas sobre rotina, orçamento e preparo; o contato via WhatsApp só é liberado para quem atinge a pontuação de "alto compromisso" (com limite de tentativas).
- 📚 **Seção "Conheça a raça de verdade"** — alerta sobre coluna sensível (IVDD), expectativa de vida, custo mensal médio e outros pontos que toda família deveria saber antes de adotar.
- 🖼️ **Galeria em polaroid** — pilha de fotos com efeito de leque ao passar o mouse, vídeo em destaque com modal e placeholders para laudo de pedigree.
- 📊 **Barra de progresso "consciência"** — acompanha o scroll da página com uma trilha animada (🚶 → 🐶).
- 💬 **Botão flutuante do WhatsApp**, contadores animados, reveal on scroll, tilt 3D nos cards e microanimações em quase todo canto.
- 📱 **Totalmente responsivo**, com menu sanduíche para mobile.

## 🛠️ Stack

- **HTML5** semântico, tudo em um único arquivo (`index.html`)
- **CSS puro** (custom properties, grid, animações e transições — sem framework)
- **JavaScript vanilla** (sem dependências externas, sem bundler)
- Fontes via Google Fonts (`Quicksand` + `Nunito`)

## 📁 Estrutura

```text
├── index.html          # site inteiro (markup + estilos + scripts)
├── assets/             # fotos dos filhotes
└── LICENSE
```

## 🚀 Rodando localmente

Não tem build, não tem `npm install` — é só abrir:

```bash
git clone https://github.com/<seu-usuario>/salsichasuzano.com.br.git
cd salsichasuzano.com.br
```

Depois é só abrir o `index.html` no navegador, ou subir um servidor local simples:

```bash
python -m http.server 8000
# ou
npx serve .
```

> ⚠️ **Vídeo da galeria (embed do YouTube):** abrir o `index.html` direto do disco (`file://`) faz o navegador bloquear o iframe do YouTube por política de segurança. Para ver o vídeo funcionando, acesse sempre via servidor local (`http://localhost:8000`) ou pelo site já publicado.

## 💛 Contribuindo

Sugestões, correções e melhorias são bem-vindas! Abra uma issue ou mande um PR.

Se este projeto te ajudou ou você só achou o site bonitinho, considere deixar uma ⭐ — isso ajuda bastante a dar visibilidade ao repositório.

## 📄 Licença

Distribuído sob a licença [MIT](LICENSE).

---

**Feito com 🐾 para encontrar um lar cheio de amor.**
