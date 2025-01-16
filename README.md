# Alura Django OAuth

O **Alura Django OAuth** é um projeto desenvolvido durante um curso da **Alura**, com o objetivo de implementar autenticação e autorização utilizando o protocolo OAuth em aplicações Django. O projeto permite que os usuários façam login através de provedores de identidade, como Google ou GitHub, e explora práticas recomendadas para integrar OAuth em sistemas web.

---

## 🚀 Funcionalidades

- **Autenticação via OAuth**:
  - Login com provedores como Google ou GitHub.
  - Gerenciamento de tokens de autenticação.
- **Sistema Seguro**:
  - Utilização de tokens para autorização.
  - Integração com bibliotecas específicas para Django.
- **Base com Django**:
  - Estrutura robusta para gerenciar usuários e autenticação.

---

## 🛠️ Tecnologias Utilizadas

- **Django**: Framework principal do projeto.
- **OAuth2**: Protocolo utilizado para autenticação e autorização.
- **python-dotenv**: Para gerenciar variáveis de ambiente.
- **SQLite**: Banco de dados para armazenamento local.
- **Django Authentication Libraries**: Bibliotecas como `django-allauth` (se utilizada).

---

## 📂 Estrutura de Arquivos

```plaintext
/
├── setup/             # Configurações do Django
├── templates/         # Arquivos HTML para renderização
├── static/            # Arquivos estáticos (CSS, JS, imagens)
├── .env               # Arquivo de variáveis de ambiente
├── requirements.txt   # Dependências do projeto
└── manage.py          # Script de gerenciamento do Django
