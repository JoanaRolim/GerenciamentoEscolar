# Sistema de Gerenciamento de Escola usando Django

# Sobre o Projeto

### A. Admin Podem

1. Consulte os gráficos de resumo geral do desempenho dos alunos, desempenho da equipe, cursos, disciplinas, férias, etc.
2. Gerenciar equipes (adicionar, atualizar e excluir)
3. Gerenciar alunos (adicionar, atualizar e excluir)
4. Gerenciar Curso (Adicionar, Atualizar e Excluir)
5. Gerenciar assuntos (adicionar, atualizar e excluir)
6. Gerenciar sessões (adicionar, atualizar e excluir)
7. Veja a frequência do aluno
8. Revise e responda aos comentários dos alunos/funcionários
9. Revisar (Aprovar/Rejeitar) Aluno/Funcionário

### B. Funcionários/Professores Podem

1. Veja os Gráficos de Resumo Geral relacionados a seus alunos, suas disciplinas, status de licença, etc.
2. Registrar/atualizar a frequência dos alunos
3. Adicionar/Atualizar Resultado
4. Solicitar Licença
5. Envie feedback

### C. Estudantes Podem

1. Veja os Gráficos de Resumo Geral relacionados à sua frequência, suas disciplinas, status de licença, etc.
2. Ver Presença
3. Ver Resultado
4. Solicitar licença
5. Envie feedback

## Como instalar e rodar esse projeto?

### Pre-Requisitos:

1. Instale Python
2. [ https://www.python.org/downloads/ ]
3. Instale Pip (Package Manager)
   [ https://pip.pypa.io/en/stable/installing/ ]

*Alternative to Pip is Homebrew*

### Instalação

**1. Crie uma Pasta para salvar o projeto**

**2. Crie um Ambiente Virtual**

Install Virtual Environment First

```
$  pip install virtualenv
```

Create Virtual Environment

For Windows

```
$  python -m venv venv
```

For Mac

```
$  python3 -m venv venv
```

Activate Virtual Environment

For Windows

```
$  source venv/scripts/activate
```

For Mac

```
$  source venv/bin/activate
```

**3. Clone o projeto**

$  git clone https://github.com/JoanaRolim/GerenciamentoEscolar.git

Then, Enter the project

```
$  cd django-student-management-system
```

**4. Install Requirements from 'requirements.txt'**

```python
$  pip install -r requirements.txt
```

**5. Add the hosts**

- Got to settings.py file
- Then, On allowed hosts, Add [‘*’].

```python
ALLOWED_HOSTS = ['*']
```

*No need to change on Mac.*

**6. Now Run Server**

Command for PC:

```python
$ python manage.py runserver
```

Command for Mac:

```python
$ python3 manage.py runserver
```

**7. Login Credentials**

Create Super User (HOD)

```
$  python manage.py createsuperuser
```

Adicione Email, Usuário e Senha

**Credenciais Cadastradas**

* SuperAdmin*
Email: admin@gmail.com
Senha: admin

*Funcionário*
Email: staff@gmail.com
Senha: staff

*Estudante*
Email: student@gmail.com
Senha: student
# GerenciamentoEscolar
# GerenciamentoEscolar
