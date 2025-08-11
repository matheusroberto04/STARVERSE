# STARVERSE

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-4.x-green)](https://www.djangoproject.com/)
[![License](https://img.shields.io/badge/license-MIT-lightgrey)](LICENSE)

Projeto desenvolvido com **Django** para gerenciamento de imagens em uma galeria, com área administrativa protegida e suporte para upload de arquivos.

## 🚀 Tecnologias utilizadas
- **Python 3.10+**
- **Django 4.x**
- HTML5 / CSS3
- SQLite3 (banco de dados padrão do Django)

---

## 📦 Pré-requisitos

Antes de começar, tenha instalado:
- [Python 3.10 ou 3.11](https://www.python.org/downloads/)
- [pip](https://pip.pypa.io/en/stable/)
- [Visual Studio Code](https://code.visualstudio.com/) (opcional, mas recomendado)

---

# Instalação — passo a passo

-> Verifique a versão do Python
Confirme que está usando Python 3.10 ou 3.11:

`python --version`

-> Instale o virtualenv

`pip install virtualenv`

-> Crie a máquina virtual
(Use .venv ou outro nome à sua escolha)

`python -m virtualenv .venv`

-> Ative a virtualenv

`.venv\Scripts\activate`

-> Selecione o interpretador no VS Code
Abra o VS Code e pressione Ctrl + Shift + P → Python: Select Interpreter → escolha a versão/venv criada.

Instale as dependências

`pip install -r requirements.txt`

Execute as migrations

`python manage.py migrate`

Execute o servidor

`python manage.py runserver`

O site ficará disponível em http://127.0.0.1:8000/.

# Criar usuário administrador (para inserir imagens na galeria):

Para acessar a área administrativa e fazer upload de imagens, crie um superusuário:

`python manage.py createsuperuser`

Siga os prompts e informe username, email e password.
Se aparecer uma mensagem informando que a senha é fraca, confirme digitando Y (aceitar o bypass) — ou escolha uma senha mais forte.

Acesse o admin em:

`http://127.0.0.1:8000/admin`

# Agradecimentos / Observação final
Obrigado por testar o projeto — espero que goste do site! Foi um projeto muito bem feito.
Se quiser, eu deixo esse README mais personalizado (adicione badges, instruções de deploy, variáveis de ambiente, etc).
