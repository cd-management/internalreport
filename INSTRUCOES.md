# Como publicar o Registo de Intervenção no GitHub Pages

## Passos (5 minutos)

### 1. Criar repositório no GitHub

1. Vai a **github.com** e faz login com a conta `paulomarcelino-pm`
2. Clica no **+** (canto superior direito) → **New repository**
3. Preenche:
   - **Repository name:** `digiwest-registo`
   - **Public** (seleciona esta opção)
   - **NÃO** marques nenhuma das opções de inicialização
4. Clica **Create repository**

---

### 2. Fazer upload do ficheiro

1. Na página do repositório recém-criado, clica em **uploading an existing file**
2. Arrasta o ficheiro `index.html` para a área de upload
3. Em baixo, clica **Commit changes**

---

### 3. Ativar GitHub Pages

1. No repositório, clica em **Settings** (tab no topo)
2. No menu lateral, clica em **Pages**
3. Em **Source**, seleciona **Deploy from a branch**
4. Em **Branch**, seleciona **main** → pasta **/ (root)**
5. Clica **Save**

---

### 4. Obter o link

Após 1-2 minutos, o link ficará disponível em:

```
https://paulomarcelino-pm.github.io/digiwest-registo/
```

---

### 5. Partilhar no OneDrive

1. Cria um ficheiro de texto no OneDrive com o nome `Registo de Intervenção - LINK.txt`
2. Dentro escreve o link: `https://paulomarcelino-pm.github.io/digiwest-registo/`
3. A equipa clica no link → abre no browser → tudo funciona

---

## Notas importantes

- O formulário guarda os dados **localmente em cada browser** (localStorage)
- Cada pessoa tem os seus próprios dados guardados no seu browser
- Para partilhar um registo preenchido: usar **Exportar JSON** → partilhar o ficheiro JSON → outro utilizador faz **Importar JSON**
- Para atualizar o formulário no futuro: basta substituir o `index.html` no repositório GitHub
