# 👨🏻‍💻🧨 Fallout Terminal Hacker — Word Filter System

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with](https://img.shields.io/badge/Made%20with-HTML%20%26%20CSS%20%26%20JS-blue)](#)
[![Status](https://img.shields.io/badge/Status-Online-brightgreen)](https://lrpaulino.github.io/fallout-terminal-hacker)

> A browser-based static tool to crack terminal passwords in *Fallout 4*, *Fallout 76*, and *Fallout: New Vegas*.  
> Paste the terminal's word list, register your guesses with the "likeness" (correct letters) score, and let the script automatically eliminate invalid candidates.

![Screenshot do Terminal Hacker](https://github.com/lrpaulino/fallout-terminal-hacker/blob/main/print.png?raw=true)

---

## 📖 Sobre o Projeto

No universo de *Fallout*, hackear terminais RobCo envolve escolher palavras de uma lista e receber um número indicando quantas letras estão na posição correta. Este **auxiliar de hacking** replica essa mecânica e faz o trabalho pesado para você:

- Cole a lista de palavras exibida no terminal do jogo.
- Informe cada palavra que você tentou e o número de letras corretas retornado pelo jogo.
- A ferramenta filtra automaticamente todas as palavras que **não** são compatíveis com as tentativas registradas, deixando apenas as candidatas viáveis.

Além disso, ela conta com uma interface **CRT retrô**, animações de scanline e um visual que homenageia os terminais da RobCo Industries.

---

## 🚀 Como Usar

1. **Acesse a página** – [Link para o GitHub Pages ou abra o arquivo HTML localmente].
2. **Carregue a lista de palavras** – Cole no campo *"Lista de Palavras do Terminal"* as palavras que aparecem no jogo.  
   Você pode separá-las por quebra de linha, vírgula ou espaço. Exemplo:

ACCESS, ACTION, AMOUNT, ANSWER, BATTERY, BOTTLE, CAPTURE

Clique em **"Carregar Lista"**.
3. **Registre suas tentativas**:
- No campo *"Palavra tentada"*, digite a palavra que você escolheu no terminal.
- No campo *"Corretas"*, coloque o número que o jogo mostrou (quantas letras estão na posição certa).
- Clique em **"Adicionar"** ou pressione `Enter`.
4. **Veja os candidatos restantes** – A lista à direita atualiza automaticamente, mostrando apenas as palavras que ainda podem ser a senha.
5. **Use a "Dica Escondida"** – Se quiser simular a função `[ ]` do jogo, clique no botão para remover aleatoriamente uma palavra da lista de candidatas (sem revelar qual).
6. **Repita** – Continue testando palavras até restar apenas uma candidata. Essa é a sua senha!

> **Dica:** Você pode usar o botão **"Auto-Sugerir Candidata"** (caso tenha implementado) para preencher o campo de tentativa com a primeira palavra da lista, agilizando o processo.

---

## ✨ Funcionalidades

- ✅ **Filtragem automática** – Baseada em todas as tentativas registradas.
- ✅ **Suporte a comprimento variável** – Detecta automaticamente o tamanho das palavras (ex: 7 letras) e ignora palavras de tamanho diferente.
- ✅ **Lista de tentativas** – Histórico completo com número da tentativa, palavra e pontuação.
- ✅ **Barra de progresso** – Mostra quantas palavras já foram eliminadas.
- ✅ **Dica escondida** – Remove aleatoriamente uma palavra candidata (fiel ao jogo).
- ✅ **Interface retrô** – Estilo CRT com scanlines, fonte monoespaçada e cores verde/âmbar.
- ✅ **Relógio em tempo real** – Para manter a imersão.
- ✅ **Totalmente estático** – Não requer servidor ou instalação. Basta abrir o arquivo HTML.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** – Estrutura semântica.
- **CSS3** – Estilização com efeitos de scanline, animações e layout responsivo.
- **JavaScript (ES6+)** – Lógica de filtragem, manipulação do DOM e interatividade.
- **Fonte** – `Courier New` para visual autêntico de terminal.

---

## 🖥️ Como Contribuir

Contribuições são super bem-vindas! Siga os passos:

1. Faça um *fork* deste repositório.
2. Crie uma *branch* para sua feature: `git checkout -b minha-feature`.
3. Faça as alterações e *commits*: `git commit -m 'Adiciona nova feature'`.
4. Envie para a *branch*: `git push origin minha-feature`.
5. Abra um *Pull Request*.

Sugestões de melhorias:
- Implementar suporte a múltiplos idiomas (i18n).
- Adicionar persistência local com `localStorage`.
- Criar um modo "automático" que tenta todas as combinações.
- Melhorar a acessibilidade.

---

## 📄 Licença

Este projeto está licenciado sob a licença **MIT**. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 🙏 Créditos

- Inspirado na franquia *Fallout* da Bethesda Softworks.
- Agradecimentos especiais à comunidade de modding e fãs.

---

**Happy Hacking!** 🕹️🔐
