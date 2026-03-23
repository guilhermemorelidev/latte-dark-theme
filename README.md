# ☕ Aesthetic Latte Dark

Tema escuro para o VS Code com paleta de cores inspirada em café — tons quentes de âmbar, marrom e creme sobre um fundo quase preto. Portado do KDE Plasma.

![Preview do tema](./screenshots/preview.png)

---

## 🎨 Paleta de cores

| Elemento | Cor | Preview |
|---|---|---|
| Background | `#0C0B09` | ![](https://placehold.co/60x16/0C0B09/0C0B09) |
| Foreground | `#F0E9DF` | ![](https://placehold.co/60x16/F0E9DF/F0E9DF) |
| Âmbar (keywords) | `#B48246` | ![](https://placehold.co/60x16/B48246/B48246) |
| Dourado (classes) | `#C89641` | ![](https://placehold.co/60x16/C89641/C89641) |
| Verde (strings) | `#5FA564` | ![](https://placehold.co/60x16/5FA564/5FA564) |
| Roxo (números) | `#916EA0` | ![](https://placehold.co/60x16/916EA0/916EA0) |
| Azul (tipos) | `#7A9EC2` | ![](https://placehold.co/60x16/7A9EC2/7A9EC2) |
| Vermelho (erros) | `#C85555` | ![](https://placehold.co/60x16/C85555/C85555) |

---

## ✨ O que está incluído

- Colorização completa do **editor** (cursor, seleção, highlight, bracket matching)
- **Activity bar**, **sidebar**, **status bar** e **tabs** totalmente tematizados
- **Terminal** com paleta ANSI completa (16 cores)
- **Suporte semântico** — colorização avançada via `semanticTokenColors`
- Linguagens com suporte dedicado: **TypeScript**, **JavaScript**, **C#**, **Python**, **Svelte**, **HTML**, **CSS/SCSS**, **JSON**, **Markdown**, **Shell**, **Rust**
- Bracket pair colorization com 6 cores distintas
- Decoradores e anotações em roxo
- Parâmetros de função em itálico

---

## 📦 Instalação

### Via VS Code Marketplace
> Em breve disponível no marketplace.

### Manual (VSIX)

1. Baixe o arquivo `.vsix` na página de [Releases](https://github.com/guilhermemorelidev/latte-dark-theme/releases)
2. No VS Code, abra o Command Palette: `Ctrl+Shift+P`
3. Execute: `Extensions: Install from VSIX...`
4. Selecione o arquivo baixado

### Via linha de comando

```bash
code --install-extension guilhermemorelidev.aesthetic-latte-dark
```

---

## ⚙️ Ativando o tema

Após instalar, pressione `Ctrl+K` → `Ctrl+T` e selecione **Aesthetic Latte Dark**.

Ou via Command Palette (`Ctrl+Shift+P`):
```
Preferences: Color Theme → Aesthetic Latte Dark
```

---

## 🖥️ Linguagens testadas

O tema foi desenvolvido e testado com foco em:

- **Svelte** — tags, atributos e interpolações
- **TypeScript / JavaScript** — tipos, interfaces, generics, decoradores
- **C#** — classes, namespaces, métodos, LINQ
- **Python** — self, magic methods, type hints
- **HTML / CSS / SCSS** — seletores, propriedades, variáveis CSS
- **JSON** — chaves e valores
- **Markdown** — headings, bold, italic, código, links

---

## 🛠️ Desenvolvimento local

```bash
# Clone o repositório
git clone https://github.com/guilhermemorelidev/latte-dark-theme.git
cd latte-dark-theme

# Abra no VS Code
code .

# Pressione F5 para abrir a Extension Development Host
# Ative o tema com Ctrl+K → Ctrl+T → "Aesthetic Latte Dark"
```

Qualquer alteração em `themes/latte-color-theme.json` é aplicada automaticamente na janela de desenvolvimento.

---

## 🤝 Contribuindo

Encontrou alguma linguagem com colorização ruim? Abra uma [issue](https://github.com/guilhermemorelidev/latte-dark-theme/issues) ou um pull request com a correção. Contribuições são bem-vindas!

---

## 📄 Licença

MIT © [Guilherme Moreli](https://github.com/guilhermemorelidev)
