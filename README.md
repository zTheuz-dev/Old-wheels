# Git e GitHub — Fluxo de Trabalho da Equipe

## 📌 Objetivo

Organizar o desenvolvimento do projeto para que cada integrante consiga trabalhar separadamente sem alterar o código dos outros integrantes.

---

# 🌿 O que é uma Branch?

Uma branch é uma “cópia” do projeto principal onde cada integrante desenvolve sua parte separadamente.

A branch principal do projeto normalmente é:

```bash
main
```

Cada integrante utiliza sua própria branch:

```bash
front-Wessler
front-Semmer
front-Aguiar
front-Agapito
```

---

# 🚀 Primeira Configuração (Primeiro Uso)

## 1️⃣ Clonar o repositório

```bash
git clone https://github.com/zTheuz-dev/Old-wheels.git
```

---

## 2️⃣ Entrar na pasta do projeto

```bash
cd Old-wheels
```

---

## 3️⃣ Verificar branches disponíveis

```bash
git branch -a
```

---

## 4️⃣ Conectar na sua branch

Exemplo:

```bash
git checkout -b front-Aguiar origin/front-Aguiar
```

Isso conecta sua máquina com sua branch do GitHub.

---

# 🔄 Fluxo do Dia a Dia

## 1️⃣ Entrar na pasta do projeto

```bash
cd Old-wheels
```

---

## 2️⃣ Ir para sua branch

```bash
git checkout front-Aguiar
```

---

## 3️⃣ Atualizar sua branch

```bash
git pull origin front-Aguiar
```

Isso baixa as alterações mais recentes da sua branch.

---

## 4️⃣ Fazer alterações

Exemplos:

* criar páginas;
* editar CSS;
* adicionar imagens;
* desenvolver funcionalidades.

---

## 5️⃣ Verificar alterações

```bash
git status
```

---

## 6️⃣ Adicionar alterações

```bash
git add .
```

---

## 7️⃣ Salvar alterações

```bash
git commit -m "Descrição da alteração"
```

Exemplo:

```bash
git commit -m "Criada seção de veículos antigos"
```

---

## 8️⃣ Enviar alterações para o GitHub

```bash
git push origin front-Aguiar
```

Isso envia seu projeto atualizado para sua branch no GitHub.

---

# ✅ Regras da Equipe

* Não trabalhar diretamente na `main`;
* Cada integrante deve usar sua própria branch;
* Sempre atualizar antes de começar;
* Fazer commits com descrições claras;
* Testar antes de enviar alterações.

---

# 📌 Resumo do Fluxo Diário

```text
Entrar no projeto
      ↓
Checkout da sua branch
      ↓
Git Pull
      ↓
Fazer alterações
      ↓
Git Add
      ↓
Git Commit
      ↓
Git Push
```

Fluxo resumido:

```bash
git checkout front-Aguiar
git pull origin front-Aguiar

# desenvolver...

git add .
git commit -m "Descrição da alteração"
git push origin front-Aguiar
```
