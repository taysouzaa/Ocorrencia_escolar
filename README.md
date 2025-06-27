# 📚 R.O.E – Registro de Ocorrência Escolar

---

### 👩‍💻 Desenvolvido por: **Taynara Souza**

---

## 🚀 Sobre o Projeto

**R.O.E – Registro de Ocorrência Escolar** é um projeto pessoal desenvolvido para a **Escola Gustavo Peccinini**, com o objetivo de automatizar o fluxo de registro de ocorrências escolares e pareceres pedagógicos.  
A automação integra formulários online, planilhas Google Sheets e envio automático de e-mails, facilitando a comunicação entre professores e coordenação pedagógica.

---

## 🎯 Objetivo

- Automatizar o registro de ocorrências feitas pelos professores;
- Armazenar os dados na planilha `registro_ocorrencia_escolar`;
- Enviar e-mail automático com link para parecer pedagógico;
- Salvar os pareceres na planilha `parecer_pedagogico`;
- Pré-preencher campos do parecer via URL;
- Automatizar todo o processo com n8n.

---

## ⚙️ Funcionalidades

- ✅ Formulário para professores registrarem ocorrências;  
- ✅ Armazenamento automático em Google Sheets;  
- ✅ E-mail automático para coordenação com link personalizado;  
- ✅ Formulário para parecer pedagógico com campos pré-preenchidos;  
- ✅ Fluxos totalmente testados e funcionando.

---

## 🗂️ Estrutura das Planilhas

| Nome da Planilha            | Finalidade                              |
|----------------------------|----------------------------------------|
| `registro_ocorrencia_escolar` | Registro das ocorrências dos professores |
| `parecer_pedagogico`          | Armazenamento dos pareceres preenchidos |

---

## 🛠️ Tecnologias Utilizadas

- [n8n](https://n8n.io/) — Automação de workflows  
- Google Forms — Coleta de dados  
- Google Sheets — Armazenamento  
- Gmail — Envio automático de e-mails  

---

## 📋 Como Usar

1. Configure os formulários Google Forms (ocorrência e parecer pedagógico).  
2. Configure as planilhas no Google Sheets com os nomes:  
   - `registro_ocorrencia_escolar`  
   - `parecer_pedagogico`  
3. Importe o workflow no n8n (arquivo JSON na pasta `/workflows/` ou configure manualmente).  
4. Ajuste as credenciais Google e Gmail no n8n.  
5. Teste o fluxo preenchendo os formulários.

---

## 🤝 Contribuição & Contato

Este é um projeto pessoal, mas contribuições são bem-vindas!  
Para dúvidas, sugestões ou melhorias, abra uma issue.

📧 Para contato: taynara.souza.dev@gmail.com


---

⭐ Obrigada por visitar o projeto! ⭐
