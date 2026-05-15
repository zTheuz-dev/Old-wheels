````md
# Git e GitHub — Fluxo de Trabalho da Equipe

## 📌 Objetivo
Organizar o desenvolvimento do projeto para que cada integrante consiga trabalhar separadamente sem alterar o código dos outros integrantes.

---

# 🌿 O que é uma Branch?

Uma branch é uma “cópia” do projeto principal onde cada integrante pode desenvolver sua parte separadamente.

A branch principal do projeto normalmente é:
```bash
main
````

Cada integrante deve criar sua própria branch:

```bash
front-Wessler
front-Semmer
front-Aguiar
front-Agapito



```

---

# 🔄 Fluxo de Trabalho

## 1️⃣ Clonar o repositório

Baixar o projeto do GitHub para o computador:

```bash
git clone LINK_DO_REPOSITORIO
```

---

## 2️⃣ Entrar na pasta do projeto

```bash
cd nome-do-projeto
```

---

## 3️⃣ Atualizar o projeto

Sempre atualizar antes de começar:

```bash
git pull
```

Isso baixa as alterações mais recentes feitas pela equipe.

---

## 4️⃣ Criar sua branch

```bash
git checkout -b nome-da-branch
```

Exemplo:

```bash
git checkout -b frontend-matheus
```

---

## 5️⃣ Fazer alterações

Exemplo:

* criar páginas;
* editar CSS;
* adicionar imagens;
* desenvolver funcionalidades.

---

## 6️⃣ Verificar alterações

```bash
git status
```

Mostra os arquivos modificados.

---

## 7️⃣ Adicionar alterações

```bash
git add .
```

Adiciona todos os arquivos alterados.

---

## 8️⃣ Salvar alterações

```bash
git commit -m "Descrição da alteração"
```

Exemplo:

```bash
git commit -m "Criada seção de veículos antigos"
```

O commit funciona como um “salvamento” do progresso.

---

## 9️⃣ Enviar alterações para o GitHub

```bash
git push origin nome-da-branch
```

Exemplo:

```bash
git push origin frontend-matheus
```

---

# 🔥 Pull Request (PR)

Depois de terminar sua parte, deve ser criado um Pull Request no GitHub.

O Pull Request serve para:

* revisar alterações;
* verificar erros;
* aprovar o código;
* juntar a branch com a `main`.

Exemplo:

```text
frontend-matheus → main
```

---

# 🔀 Merge

O Merge acontece quando o Pull Request é aprovado.

Ele junta:

```text
Sua branch + main
```

Resultado:

```text
main atualizada
```

---

# ⚠️ Conflitos

Caso duas pessoas alterem a mesma linha de código, o Git pode gerar conflito.

Será necessário escolher:

* qual código manter;
* ou juntar os dois manualmente.

---

# ✅ Regras da Equipe

* Não trabalhar diretamente na `main`;
* Cada integrante deve usar sua própria branch;
* Sempre usar `git pull` antes de começar;
* Fazer commits com descrições claras;
* Testar antes de enviar alterações.

---

# 🚀 Resumo do Fluxo

```text
Clonar projeto
      ↓
Git Pull
      ↓
Criar branch
      ↓
Fazer alterações
      ↓
Git Add
      ↓
Git Commit
      ↓
Git Push
      ↓
Pull Request
      ↓
Merge na main
```

```
```
