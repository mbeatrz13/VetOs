<div align="center">

# 🐾 VetOS
### Sistema de Gestão Veterinária

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Python](https://img.shields.io/badge/Python-3.11+-3776AB?logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-4.x-092E20?logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-18.x-61DAFB?logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15+-4169E1?logo=postgresql&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)

*Plataforma completa para gestão de clínicas e hospitais veterinários*

</div>

---

## 📋 Sobre o Projeto

O **VetOS** é um sistema web de gestão veterinária desenvolvido para centralizar e otimizar os processos de clínicas e hospitais veterinários. Da recepção ao prontuário, do estoque à emissão de receitas, o VetOS oferece uma solução integrada para o dia a dia do profissional veterinário.

---

## ✨ Funcionalidades

| Módulo | Descrição |
|--------|-----------|
| 🐶 **Pacientes** | Cadastro completo de animais com histórico, espécie, raça, peso e dados clínicos |
| 👤 **Tutores** | Gestão de tutores com vínculo a múltiplos animais e histórico de atendimentos |
| 📅 **Agendamentos** | Agendamento de consultas com controle de disponibilidade e notificações |
| 📋 **Prontuário Eletrônico** | Registro de anamnese, exames, diagnósticos e evolução clínica |
| 💊 **Estoque / Farmácia** | Controle de medicamentos, vacinas e insumos com alertas de validade e estoque mínimo |
| 📄 **Receitas e Laudos** | Emissão de receitas veterinárias e laudos de exames com assinatura digital |
| 💰 **Financeiro** | Controle de receitas, despesas, orçamentos e faturamento por atendimento |

---

## 🛠️ Stack Tecnológica

**Backend**
- [Python 3.11+](https://www.python.org/)
- [Django 4.x](https://www.djangoproject.com/) + Django REST Framework
- [PostgreSQL 15+](https://www.postgresql.org/)

**Frontend**
- [React 18.x](https://reactjs.org/)
- [Vite](https://vitejs.dev/) (bundler)

---

## 🚀 Como Rodar o Projeto

### Pré-requisitos

- Python 3.11+
- Node.js 18+
- PostgreSQL 15+
- Git

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/vetos.git
cd vetos
```

### 2. Configuração do Backend

```bash
cd backend

# Crie e ative o ambiente virtual
python -m venv venv
source venv/bin/activate  # Linux/Mac
# venv\Scripts\activate   # Windows

# Instale as dependências
pip install -r requirements.txt

# Configure as variáveis de ambiente
cp .env.example .env
# Edite o .env com suas credenciais do banco de dados

# Execute as migrações
python manage.py migrate

# Crie um superusuário
python manage.py createsuperuser

# Inicie o servidor
python manage.py runserver
```

### 3. Configuração do Frontend

```bash
cd frontend

# Instale as dependências
npm install

# Configure as variáveis de ambiente
cp .env.example .env

# Inicie o servidor de desenvolvimento
npm run dev
```

### 4. Acesse o sistema

- **Frontend:** http://localhost:5173
- **Backend API:** http://localhost:8000/api
- **Admin Django:** http://localhost:8000/admin

---

## 📁 Estrutura do Projeto

```
vetos/
├── backend/
│   ├── apps/
│   │   ├── pacientes/
│   │   ├── tutores/
│   │   ├── agendamentos/
│   │   ├── prontuarios/
│   │   ├── estoque/
│   │   ├── financeiro/
│   │   └── documentos/
│   ├── config/
│   ├── requirements.txt
│   └── manage.py
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── hooks/
│   ├── package.json
│   └── vite.config.js
└── README.md
```

---

## 🗺️ Roadmap

- [x] Estrutura base do projeto
- [ ] Módulo de Pacientes e Tutores
- [ ] Módulo de Agendamentos
- [ ] Prontuário Eletrônico
- [ ] Módulo de Estoque
- [ ] Financeiro
- [ ] Emissão de Receitas e Laudos
- [ ] Testes automatizados
- [ ] Deploy em produção

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/minha-feature`)
3. Commit suas mudanças (`git commit -m 'feat: adiciona minha feature'`)
4. Push para a branch (`git push origin feature/minha-feature`)
5. Abra um Pull Request

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<div align="center">
  Feito com ❤️ para a medicina veterinária
</div>
