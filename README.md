# R.O.E – Registro de Ocorrência Escolar

Projeto desenvolvido para a Escola Gustavo Peccinini, com o objetivo de automatizar o registro de ocorrências escolares e pareceres pedagógicos.  
A solução integra formulários Google, planilhas e envio automático de e-mails, otimizando a comunicação entre professores e coordenação.

---

## Objetivos

- Automatizar o registro de ocorrências
- Armazenar dados em planilhas no Google Sheets
- Enviar e-mails automáticos com link para parecer pedagógico
- Pré-preencher campos do parecer via URL
- Integrar e automatizar o processo com n8n

---

## Funcionalidades

- Registro de ocorrências via formulário  
- Armazenamento automático dos dados  
- Envio de e-mail com link personalizado  
- Formulário de parecer com preenchimento dinâmico  
- Fluxos no n8n 100% funcionais

---

## Estrutura das Planilhas

| Planilha                    | Finalidade                             |
|----------------------------|----------------------------------------|
| `registro_ocorrencia_escolar` | Registra ocorrências enviadas pelos professores |
| `parecer_pedagogico`          | Registra os pareceres da coordenação         |

---

## Tecnologias Utilizadas

- [n8n](https://n8n.io) – Plataforma de automação
- Google Forms – Coleta de dados
- Google Sheets – Armazenamento das respostas
- Gmail – Envio automático de mensagens

---

## Fluxos de Automação (n8n)

### 📌 Registro de Ocorrência Escolar

Fluxo responsável por:
1. Capturar dados do formulário de ocorrência
2. Registrar na planilha do Google
3. Enviar e-mail automático para a coordenação

![n8n fluxo2](https://github.com/user-attachments/assets/7bc22050-d142-42f6-965e-05292a9e022c)


---

### 📌 Parecer Pedagógico

Fluxo responsável por:
1. Receber o parecer preenchido via formulário
2. Registrar os dados na planilha

![n8n fluxo](https://github.com/user-attachments/assets/f9ad3119-7d8a-417b-b07f-a37f8ac1a7b6)


---


## Contato

📧 taynara.souza.dev@gmail.com  
🔗 www.linkedin.com/in/taynara-correia-souza

---

Obrigada por visitar o projeto!
