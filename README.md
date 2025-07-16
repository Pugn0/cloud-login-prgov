### 📁 Nome do diretório:

```
cloud-login-prgov
```

---

### 📄 README.md

````markdown
# 🌐 Cloud Login PR.GOV.BR

Este projeto fornece um arquivo JSON contendo credenciais de exemplo e URLs de login para sistemas do governo do Paraná (`*.pr.gov.br`). Ideal para testes, automações ou integração com ferramentas de debug/autenticação.

## 📁 Estrutura do JSON

Cada entrada possui os seguintes campos:

- `url`: URL completa da página de login
- `username`: Nome de usuário (CPF)
- `password`: Senha
- `line`: Linha formatada para uso rápido (com delimitadores)

### 🧪 Exemplo:
```json
[
  {
    "url": "https://www.nsb.pr.gov.br/portal/login",
    "username": "093.229.919-92",
    "password": "jesustiamo",
    "line": "https://www.nsb.pr.gov.br/portal/login|093.229.919-92|jesustiamo"
  },
  {
    "url": "https://authz.identidadedigital.pr.gov.br/cidadao_authz/authentication.html",
    "username": "86336280586",
    "password": "claudio2323",
    "line": "https://authz.identidadedigital.pr.gov.br/cidadao_authz/authentication.html:86336280586:claudio2323"
  }
]
````

## ⚠️ Aviso

> **Este conteúdo é apenas para fins educacionais e de teste. Não utilize em ambientes de produção sem autorização.**

## 📬 Contato e Créditos

* Telegram: [@pugno\_dev](https://t.me/pugno_dev) | [@pugno\_fc](https://t.me/pugno_fc)


