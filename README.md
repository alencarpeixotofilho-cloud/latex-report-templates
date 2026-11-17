# Templates LaTeX para Relatórios Técnicos

![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white) ![Licença MIT](https://img.shields.io/badge/licen%C3%A7a-MIT-green?style=flat-square) ![Status](https://img.shields.io/badge/status-em%20constru%C3%A7%C3%A3o-orange?style=flat-square)

> Modelos LaTeX limpos e configuráveis para relatórios técnicos, pareceres e apresentações.

## 📌 Visão geral

Conjunto de modelos para documentos de avaliação educacional: relatório de desempenho, parecer técnico, nota técnica e apresentação Beamer. A identidade visual (cores, logotipo, fontes) é definida em um único arquivo de configuração.

## ✨ Funcionalidades

- Relatório técnico com capa, sumário e seções padronizadas
- Parecer e nota técnica
- Apresentação Beamer
- Cores e logotipo configuráveis em um único arquivo
- Suporte completo a português (pt-BR)

## 🗂️ Estrutura do repositório

```text
templates-latex-relatorios/
├── relatorio/
├── parecer/
├── beamer/
├── identidade.sty  # cores, fontes e logotipo
├── LICENSE
└── README.md
```

## 🚀 Como usar

```bash
cd relatorio && latexmk -pdf relatorio.tex
```

## 🔒 Dados e privacidade

Este repositório **não contém dados reais** de estudantes, docentes ou instituições.
Todos os exemplos usam **dados sintéticos** gerados pelo próprio projeto
(`exemplos/gerar_dados_exemplo`), com identificadores fictícios (`Estudante 001`, `Item 001`…).
Os itens de prova usados nos exemplos são inventados para fins de demonstração.

## 🛣️ Roadmap

- [ ] Modelo de relatório
- [ ] Modelo de parecer
- [ ] Modelo Beamer
- [ ] Arquivo de identidade visual
- [ ] Galeria de exemplos em PDF

## 📄 Licença

Distribuído sob a licença MIT. Veja [`LICENSE`](LICENSE).
