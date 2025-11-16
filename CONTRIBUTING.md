# 📄 **CONTRIBUTING.md**

````markdown
# Guia de Contribuição — Sistema Universidade

Bem-vindo(a) ao repositório do **Projeto Integrador 3 – ADS – Sistema Universidade**!  
Este documento explica, de forma simples e direta, como qualquer pessoa pode contribuir com o projeto, mesmo iniciantes em Git.

---

# 👥 Colaboradores do Projeto

- **Anderson Chrispim da Silva**
- **Diego Eiji de Menezes**
- **Gustavo Lopes**
- **Flavia R M Biagioni**
- **Andre Zicatti Leite**

Se você está nesta lista, você já tem autorização para contribuir diretamente ao projeto.

---

# 🛠️ 1. Pré-requisitos

Antes de começar, você deve:

1. Ter uma conta no GitHub  
2. Instalar o Git  
3. Configurar seu nome e e-mail:  
   ```bash
   git config --global user.name "Seu Nome"
   git config --global user.email "seuemail@exemplo.com"
````

4. Criar e registrar sua chave SSH

   ```bash
   ssh-keygen -t rsa -b 4096 -C "seuemail@exemplo.com"
   ```
5. Adicionar sua chave no GitHub (Settings → SSH and GPG Keys)

---

# 📥 2. Como clonar o repositório

Use a URL SSH (recomendado):

```bash
git clone git@github.com:ChrispimSilva/sistema_universidade.git
```

Entre na pasta:

```bash
cd sistema_universidade
```

---

# 🌱 3. Criar sua branch

Sempre trabalhe em uma branch separada:

```bash
git checkout -b seu-nome-ou-feature
```

Exemplos:

```bash
git checkout -b anderson-ajuste-layout
git checkout -b gustavo-cadastro-aluno
```

---

# ✏️ 4. Fazer alterações no código

Edite os arquivos necessários:

* HTML das telas
* CSS do protótipo
* Scripts JS
* Código Java do backend
* SQL do banco
* Documentação

Use:

```bash
git status
```

para ver o que foi modificado.

---

# ➕ 5. Adicionar arquivos ao commit

Adicionar tudo:

```bash
git add .
```

Ou adicionar arquivos específicos:

```bash
git add arquivo.html
```

---

# 📝 6. Criar o commit

```bash
git commit -m "Descrição clara do que foi alterado"
```

Exemplo:

```bash
git commit -m "Atualiza tela de cadastro de professores com novo layout"
```

---

# 🚀 7. Enviar a branch para o GitHub

```bash
git push -u origin sua-branch
```

O GitHub irá sugerir a criação de um Pull Request.

---

# 🔃 8. Criar Pull Request (PR)

1. Vá ao repositório no GitHub
2. Clique em **Compare & Pull Request**
3. Descreva as mudanças
4. Envie para revisão

A revisão pode ser feita por qualquer membro da equipe.

---

# 🔄 9. Atualizar sua cópia local

Antes de continuar trabalhando:

```bash
git pull origin main
```

Se estiver em outra branch:

```bash
git checkout sua-branch
git pull origin main
```

---

# 🧹 10. Boas práticas

* Nomeie branches de forma clara
* Mantenha commits pequenos e objetivos
* Sempre atualize sua branch antes de continuar
* Nunca faça push direto na branch **main**
* Sempre abra um Pull Request

---

Obrigado por contribuir! 💙
Qualquer dúvida, entre em contato com a equipe do Projeto Integrador.

```

