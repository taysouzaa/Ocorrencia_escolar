# 📚 Automação de Registro de Ocorrências Escolares



### 👩‍💻 Desenvolvido por: **Taynara Souza**

---

## 🚀 Sobre o Projeto

Projeto pessoal para a **Escola Gustavo Peccinini** que automatiza o registro de ocorrências escolares e o parecer pedagógico.  
Integra formulários online, planilhas no Google Sheets e envio automático de e-mails para a coordenação, otimizando a comunicação e o controle das ocorrências.

---

## 🎯 Objetivo

- Automatizar o registro de ocorrências feitas pelos professores;
- Armazenar os dados na planilha `registro_ocorrencia_escolar`;
- Enviar e-mail automático com link para parecer pedagógico;
- Salvar os pareceres na planilha `parecer_pedagogico`;
- Pré-preencher campos do parecer via URL;
- Automatizar tudo pelo n8n.

---

## ⚙️ Funcionalidades

- ✅ Formulário para professores registrarem ocorrências;  
- ✅ Armazenamento automático em Google Sheets;  
- ✅ E-mail automático para coordenação;  
- ✅ Formulário para parecer pedagógico;  
- ✅ Fluxos testados e funcionando.

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

```bash
1. Configure os formulários Google Forms (ocorrência e parecer pedagógico).
2. Configure as planilhas no Google Sheets com os nomes:
   - registro_ocorrencia_escolar
   - parecer_pedagogico
3. Importe o workflow no n8n (arquivo JSON na pasta `/workflows/` ou configure manualmente).
4. Ajuste as credenciais Google e Gmail no n8n.
5. Teste o fluxo preenchendo os formulários.

---

🤝 Contribuição
Este é um projeto pessoal, mas contribuições são bem-vindas!
Para dúvidas, sugestões ou melhorias, abra uma issue.

📬 Contato
📧 taynara.souza.dev@gmail.com

⭐ Obrigada por visitar o projeto! ⭐
