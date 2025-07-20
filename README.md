# 📝 R.O.E – Registro de Ocorrência Escolar

Automatize o registro de ocorrências e otimize a comunicação pedagógica

[![Google Sheets](https://img.shields.io/badge/Google%20Sheets-Automação-34A853?logo=google-sheets)]()
[![n8n](https://img.shields.io/badge/n8n-Automation-ff6d00?logo=n8n)]()
[![Google Forms](https://img.shields.io/badge/Google%20Forms-Formulários-673AB7?logo=google-forms)]()

Este projeto foi desenvolvido para a **Escola Gustavo Peccinini**, com o objetivo de automatizar o processo de registro de ocorrências escolares e facilitar o preenchimento de **pareceres pedagógicos**.

---

## 🎯 Objetivos

- 📌 Automatizar o envio de ocorrências escolares  
- 📊 Armazenar dados diretamente em **planilhas Google**  
- 📧 Enviar e-mails automáticos com link para preenchimento do parecer  
- 🔗 Pré-preencher campos do formulário de parecer via URL dinâmica  
- 🔄 Criar fluxos de automação com o **n8n**

---

## ✅ Funcionalidades

- Registro de ocorrências via formulário Google  
- Armazenamento automático no Google Sheets  
- Envio de e-mail com link personalizado para parecer  
- Formulário de parecer pedagógico com preenchimento automático  
- Fluxos 100% automatizados e funcionais com o **n8n**

---

## 🧾 Estrutura das Planilhas

| 📄 Planilha                    | 💡 Finalidade                             |
|------------------------------|------------------------------------------|
| `registro_ocorrencia_escolar` | Registra as ocorrências enviadas pelos professores |
| `parecer_pedagogico`          | Armazena os pareceres preenchidos pela coordenação |

---

## 🛠️ Tecnologias Utilizadas

- 🔗 [n8n](https://n8n.io) – Plataforma low-code de automação  
- 📄 Google Forms – Coleta de dados dos professores e coordenação  
- 📊 Google Sheets – Armazenamento centralizado dos dados  
- 📬 Gmail – Envio automatizado de e-mails com links personalizados

---

## ⚙️ Fluxos de Automação (n8n)

### 📌 Registro de Ocorrência Escolar

Fluxo responsável por:

1. Receber os dados enviados no formulário Google  
2. Registrar os dados na planilha `registro_ocorrencia_escolar`  
3. Enviar e-mail automático para a coordenação com link para o parecer  

![Fluxo - Registro de Ocorrência](https://github.com/user-attachments/assets/7bc22050-d142-42f6-965e-05292a9e022c)

---

### 📌 Parecer Pedagógico

Fluxo responsável por:

1. Capturar dados do parecer preenchido via formulário  
2. Registrar os dados na planilha `parecer_pedagogico`

![Fluxo - Parecer Pedagógico](https://github.com/user-attachments/assets/f9ad3119-7d8a-417b-b07f-a37f8ac1a7b6)

---

## 📬 Contato

**Taynara Souza**  
📧 [taynara.souza.dev@gmail.com](mailto:taynara.souza.dev@gmail.com)  
🔗 [linkedin.com/in/taynara-correia-souza](https://www.linkedin.com/in/taynara-correia-souza)

---

Obrigada por visitar o projeto!  
Se te ajudou ou inspirou de alguma forma, não esqueça de deixar uma ⭐ no repositório!
