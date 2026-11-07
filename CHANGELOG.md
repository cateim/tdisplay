# Changelog

Todas as mudanças notáveis do Jade DIY T-Display são documentadas neste arquivo.

O formato é baseado em [Keep a Changelog 1.1.0](https://keepachangelog.com/en/1.1.0/).
As versões seguem o esquema **CalVer `YYYY.M.R`** (ano, mês sem zero à esquerda, revisão do mês), **não** o Versionamento Semântico.

> Este changelog foi iniciado em 2026-11-06. A primeira versão resume o projeto como ele estava nessa data, reconstruída a partir do histórico do git: o repositório não tem tags, então ela leva a data do último commit.

## [Unreleased]

## [2026.11.1] - 2026-11-02

### ✨ Added

- **Base para montar a Jade DIY na T-Display**: o [Jade da Blockstream](https://github.com/Blockstream/Jade) entra como submódulo em `Jade/`, para que as modificações da placa partam sempre do código original. O firmware, as funções da carteira e as releases são trabalho da Blockstream: este repositório guarda só o ponteiro para o commit usado, sem cópia nem alteração do código, que vem com `git clone --recursive` (ou com `git submodule update --init --recursive` num clone já feito).
- **Jade fixado no commit [`a59d14c`](https://github.com/Blockstream/Jade/commit/a59d14c2b39715060e6721a309a7d49bedd3ee5b)**: um commit de desenvolvimento, 220 commits depois da release `1.0.41`, e não uma release.
- **README** com o comando que monta o repositório do zero (`git submodule add https://github.com/Blockstream/Jade.git Jade`).

### 🔧 Changed

- **Jade avançado em 2026-11-02**: de `690c8b1`, 35 commits antes da release `1.0.38`, para `a59d14c`.

[Unreleased]: https://github.com/cateim/tdisplay/compare/36df468...HEAD
[2026.11.1]: https://github.com/cateim/tdisplay/tree/36df468
