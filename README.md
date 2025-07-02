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

## Como Usar

1. Crie dois formulários no Google Forms:
   - Registro de Ocorrência
   - Parecer Pedagógico  
2. Crie as planilhas com os seguintes nomes:
   - `registro_ocorrencia_escolar`
   - `parecer_pedagogico`
3. Importe os fluxos no n8n (JSONs disponíveis na pasta `/workflows/`)
4. Configure suas credenciais de Google e Gmail no n8n
5. Teste preenchendo os formulários e observe o funcionamento do fluxo

---

## Contato

📧 taynara.souza.dev@gmail.com  
🔗 www.linkedin.com/in/taynara-correia-souza

---

Obrigada por visitar o projeto!
