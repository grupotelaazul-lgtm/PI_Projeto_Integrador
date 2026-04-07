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
├── Prototipo landing page _ Font-End/
│   ├── index.html          # Estrutura e telas da aplicação
│   ├── app.js              # Lógica e gerenciamento de dados
│   └── style.css           # Estilização e temas
│
├── EAP/
│   ├── EAP - Projeto Tela Azul V1.pdf
│   ├── EAP - Projeto Tela Azul V2.pdf
│   └── EAP - Projeto Tela Azul V3.pdf
│
├── V1 Login_Cadastro.bpm           # Diagrama BPMN — Fluxo de Login e Cadastro
├── V1 Cadastro_Assistido.bpm       # Diagrama BPMN — Cadastro Assistido
│
├── COMPILADO LEVANTAMENTO DE REQUISITOS UCE I.docx
├── Doc. Caso de Uso Atualizado.docx
├── Doc. Portabilidade.docx
├── PRODUCT DISCOVERY - PI.pdf
├── FATEC RELATÓRIO PARCIAL - UCE v1.docx
└── FATEC RELATÓRIO FINAL- UCE COMPLETO.docx
```

---

## Como Executar

Nenhuma instalação necessária. Por ser uma aplicação client-side pura:

1. Clone ou baixe este repositório
2. Abra o arquivo `Prototipo landing page _ Font-End/index.html` diretamente no navegador

> Os dados são persistidos no `localStorage` do navegador utilizado.

---

## Documentação

| Documento | Descrição |
|-----------|-----------|
| `PRODUCT DISCOVERY - PI.pdf` | Descoberta do produto e definição do problema |
| `COMPILADO LEVANTAMENTO DE REQUISITOS UCE I.docx` | Levantamento de requisitos completo |
| `Doc. Caso de Uso Atualizado.docx` | Especificação dos casos de uso |
| `Doc. Portabilidade.docx` | Requisitos de portabilidade do sistema |
| `EAP/` | Estrutura Analítica do Projeto (versões 1, 2 e 3) |
| `*.bpm` | Modelos de processos BPMN (Bizagi) |
| `FATEC RELATÓRIO FINAL- UCE COMPLETO.docx` | Relatório final do projeto |

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
