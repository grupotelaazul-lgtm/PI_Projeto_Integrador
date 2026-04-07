# Valentes de Davi — Sistema de Gerenciamento de Escolinha de Futebol

> Projeto Integrador — Engenharia de Software · FATEC · 2025

Sistema web para gerenciamento de uma escolinha de futebol, desenvolvido como Projeto Integrador do curso de Engenharia de Software da FATEC. A plataforma permite o controle de alunos, aulas, frequência e acompanhamento do desenvolvimento individual de cada aluno.

---

## Funcionalidades

- **Cadastro de Alunos** — registro completo com dados pessoais, contato e informações do responsável
- **Gerenciamento de Aulas** — criação, edição e exclusão de aulas com data e horário
- **Lista de Chamada** — registro de presença por aula, com visualização do histórico
- **Frequência** — consulta individualizada do histórico de presença de cada aluno
- **Evolução e Desenvolvimento** — avaliação de aspectos técnicos do aluno com notas de 0 a 10
- **Modo Escuro** — alternância entre tema claro e escuro, com preferência salva
- **Exportação PDF** — geração de relatórios em PDF via html2pdf.js
- **Design Responsivo** — compatível com dispositivos móveis e desktop

---

## Tecnologias

| Camada | Tecnologia |
|--------|------------|
| Estrutura | HTML5 |
| Estilização | CSS3 |
| Lógica | JavaScript (Vanilla ES6+) |
| Persistência | `localStorage` (browser) |
| PDF | [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) |

> Aplicação 100% client-side — sem necessidade de servidor ou banco de dados externo.

---

## Estrutura do Projeto

```
PI - Eng. Soft. FATEC 2025/
│
├── src/                                        # Código-fonte da aplicação
│   ├── index.html                              # Estrutura e telas
│   ├── app.js                                  # Lógica e gerenciamento de dados
│   └── style.css                               # Estilização e temas
│
├── docs/
│   ├── requisitos/
│   │   ├── levantamento-requisitos.md
│   │   └── PRODUCT DISCOVERY - PI.pdf
│   ├── casos-de-uso/
│   │   ├── casos-de-uso.md
│   │   └── portabilidade.md
│   ├── relatorios/
│   │   ├── relatorio-parcial.md
│   │   └── relatorio-final.md
│   └── guia/
│       ├── guia-projeto.md
│       └── Guia Projeto UCE.pdf
│
├── diagramas/
│   ├── bpmn/
│   │   ├── V1 Login_Cadastro.bpm               # Fluxo de Login e Cadastro
│   │   └── V1 Cadastro_Assistido.bpm           # Cadastro Assistido
│   └── eap/
│       ├── EAP - Projeto Tela AzulV1.pdf
│       └── EAP - Projeto Tela AzulV3.pdf
│
└── README.md
```

---

## Como Executar

Nenhuma instalação necessária. Por ser uma aplicação client-side pura:

1. Clone ou baixe este repositório
2. Abra o arquivo `src/index.html` diretamente no navegador

> Os dados são persistidos no `localStorage` do navegador utilizado.

---

## Documentação

| Documento | Descrição |
|-----------|-----------|
| [levantamento-requisitos.md](docs/requisitos/levantamento-requisitos.md) | Levantamento de requisitos completo |
| [casos-de-uso.md](docs/casos-de-uso/casos-de-uso.md) | Especificação dos casos de uso |
| [portabilidade.md](docs/casos-de-uso/portabilidade.md) | Requisitos de portabilidade do sistema |
| [relatorio-parcial.md](docs/relatorios/relatorio-parcial.md) | Relatório parcial UCE |
| [relatorio-final.md](docs/relatorios/relatorio-final.md) | Relatório final do projeto |
| [guia-projeto.md](docs/guia/guia-projeto.md) | Guia do Projeto UCE |
| [diagramas/eap/](diagramas/eap/) | Estrutura Analítica do Projeto (EAP) |
| [diagramas/bpmn/](diagramas/bpmn/) | Modelos de processos BPMN (Bizagi) |
| `PRODUCT DISCOVERY - PI.pdf` | Descoberta do produto e definição do problema |

---

## Integrantes

<!-- Adicione os nomes dos membros do grupo aqui -->
- Vitor Glegorio
- *(demais membros)*

---

## Instituição

**FATEC** — Faculdade de Tecnologia do Estado de São Paulo  
Curso: Engenharia de Software  
Disciplina: UCE (Unidade Curricular de Extensão) — Projeto Integrador  
Ano: 2025
