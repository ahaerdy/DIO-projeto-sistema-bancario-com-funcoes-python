# DIO-projeto-sistema-bancario-com-funcoes-python
Projeto em Python que implementa um sistema bancário CLI com funções puras, gerenciamento de usuários e contas, depósitos, saques e extrato. Tarefa do Módulo 3, do curso "Otimizando um Sistema Bancário com Funções Python" do Bootcamp Suzando Python Developer.

## 📚 Curso

- Curso "Otimizando o Sistema Bancário com Funções Python", Módulo 3 (Trabalhando com Coleções em Python) do Bootcamp Suzano Python Developer da plataforma de cursos DIO.

- **Instrutor**: Guilherme Arthur de Carvalho  
- **LinkedIn**: [@decarvalhogui](https://www.linkedin.com/in/decarvalhogui/)  
- **Linktree**: [linktr.ee/decarvalhogui](https://linktr.ee/decarvalhogui)

- Link do repositório de estudos: [Suzano - Pyhon Developer](https://github.com/ahaerdy/DIO-learning/tree/main/Suzano%20-%20Python%20Developer)

---

## 🧠 Objetivo

Reestruturar o sistema bancário básico com o uso de:

- Funções com parâmetros posicionais, nomeados e mistos;
- Validações de entrada;
- Armazenamento de usuários e contas em listas de dicionários;
- Organização modular do código;
- Regras de negócio para saque, depósito, extrato, criação de usuários e contas.

---

## 🔧 Funcionalidades Implementadas

- ✅ Depósito
- ✅ Saque com limite diário e por operação
- ✅ Visualização de extrato
- ✅ Cadastro de usuários com CPF único
- ✅ Criação de contas vinculadas a usuários
- ✅ Listagem de contas existentes

---

## 🖥️ Tecnologias Utilizadas

- Python 3.10+
- Funções puras (`def`)
- Estruturas de dados nativas (listas e dicionários)
- Formatação de strings
- `textwrap` para exibição do menu

---

## 📁 Arquivos

- `desafio.py`: código base (antes da refatoração)
- `sistema_bancario.py`: solução final com todas as funcionalidades organizadas em funções
- `README.md`: este arquivo

---

## ▶️ Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

2. Execute o programa no terminal:

```bash
python sistema_bancario.py
```

3. Siga as instruções no menu interativo.

## 📌 Regras de Negócio Implementadas

- Limite de 3 saques diários de até R$500 cada
- CPF único por usuário
- Cada conta vinculada a um único usuário
- Usuário pode ter mais de uma conta
- Saldo e extrato atualizados em cada operação

## 🏁 Aprendizados

- Durante a implementação do projeto, foi possível reforçar conceitos como:
- Uso de parâmetros * (keyword-only) e / (positional-only)
- Encapsulamento de lógica em funções puras
- Controle de fluxo com if/elif/els
- Manipulação de dados com listas e dicionários
- Boas práticas de modularização e legibilidade de código

## 📷 Imagens e Anotações

- As capturas de tela e anotações utilizadas durante o desenvolvimento estão disponíveis no arquivo notas.md com imagens no diretório /images