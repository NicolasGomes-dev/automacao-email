# Automação de E-mail

Este projeto tem como objetivo automatizar o envio de e-mails com formatação HTML e imagem incorporada, utilizando o servidor SMTP do Gmail.

---

## Funcionalidades

- Envio automático de e-mail via SMTP
- Corpo do e-mail em HTML
- inclusão de imagem externa no corpo do e-mail
- Configuração de remetente e destinatário
- Código seguro com variáveis ocultas

## Tecnologias utilizadas

- Python 3.x
- [´smptlib](https://docs.python.org/3/library/smtplib.html)
- [email.message](https://docs.python.org/3/library/email.message.html)
- HTML + CSS inline

---

## Segurança

Parta manter a senha do seu e-mail segura, utilize **variáveis de ambiente** com a biblioteca 'os':

'''bash
# Exemplo no terminal:
export EMAIL_PASSWORD='sua_senha'
