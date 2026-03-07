# 🎮 ClutchHub - Community Servers Database

🇺🇸 **[English Version below](#english-version)** | 🇧🇷 **[Versão em Português abaixo](#versão-em-português)**

---

<a id="versão-em-português"></a>
## 🇧🇷 Como adicionar o seu servidor ao ClutchHub

Bem-vindo ao banco de dados oficial do **ClutchHub**! Este repositório alimenta diretamente o nosso aplicativo desktop. Se você é dono de um servidor comunitário de Counter-Strike 2 ou CS:GO Legacy, você pode adicioná-lo aqui gratuitamente para que milhares de jogadores possam encontrá-lo.

### 📋 Passo a Passo para Adicionar seu Servidor

Nós utilizamos o sistema de **Pull Requests (PR)** do GitHub para manter a lista segura e atualizada. Siga os passos abaixo:

**Passo 1: Faça um Fork deste repositório**
Clique no botão **"Fork"** no canto superior direito desta página para criar uma cópia deste repositório na sua conta do GitHub.

**Passo 2: Edite o arquivo `servers.json`**
No seu repositório copiado (Fork), abra o arquivo `servers.json` e clique no ícone de lápis ✏️ para editá-lo.

**Passo 3: Adicione o seu Servidor**
Vá até o final da lista (antes do último `]`) e adicione as informações do seu servidor seguindo **exatamente** este formato:

```json
{
  "ip": "123.456.78.90:27015",
  "game": "CS2",
  "type": "Retake",
  "owner": "NomeDaSuaComunidade"
}
```

* **`ip`**: O IP numérico e a porta do seu servidor.
* **`game`**: Deve ser estritamente `"CS2"` ou `"CSGO"`.
* **`type`**: O modo de jogo (Ex: `"5x5"`, `"Retake"`, `"Surf"`, `"DM"`).
* **`owner`**: O nome da sua comunidade ou organização.

*(Não se esqueça de colocar uma vírgula `,` no final do servidor anterior para não quebrar o código JSON!)*

**Passo 4: Salve as alterações (Commit)**
Role até o final da página, escreva uma breve mensagem (Ex: `Add MeuServidor CS2 Retake`) e clique em **Commit changes**.

**Passo 5: Crie o Pull Request (PR)**
Volte para a página inicial do seu repositório (Fork) e clique em **"Contribute"** > **"Open pull request"**. Envie o pedido e aguarde nossa equipe aprovar!

Assim que aprovado, seu servidor aparecerá automaticamente no aplicativo **ClutchHub** de todos os usuários. 🚀

---

<a id="english-version"></a>
## 🇺🇸 How to add your server to ClutchHub

Welcome to the official **ClutchHub** database! This repository directly feeds our desktop application. If you own a Counter-Strike 2 or CS:GO Legacy community server, you can list it here for free so thousands of players can find it.

### 📋 Step-by-Step Guide to Add Your Server

We use GitHub's **Pull Request (PR)** system to keep the list secure and up to date. Follow these steps:

**Step 1: Fork this repository**
Click the **"Fork"** button in the top right corner of this page to create a copy of this repository in your GitHub account.

**Step 2: Edit the `servers.json` file**
In your forked repository, open the `servers.json` file and click the pencil icon ✏️ to edit it.

**Step 3: Add your Server**
Go to the bottom of the list (right before the last `]`) and add your server information following **exactly** this format:

```json
{
  "ip": "123.456.78.90:27015",
  "game": "CS2",
  "type": "Retake",
  "owner": "YourCommunityName"
}
```

* **`ip`**: Your server's numeric IP and port.
* **`game`**: Must be strictly `"CS2"` or `"CSGO"`.
* **`type`**: The game mode (e.g., `"5x5"`, `"Retake"`, `"Surf"`, `"DM"`).
* **`owner`**: The name of your community or organization.

*(Do not forget to add a comma `,` at the end of the previous server object to avoid breaking the JSON format!)*

**Step 4: Commit the changes**
Scroll to the bottom of the page, write a short commit message (e.g., `Add MyServer CS2 Retake`), and click **Commit changes**.

**Step 5: Create a Pull Request (PR)**
Go back to the main page of your forked repository and click **"Contribute"** > **"Open pull request"**. Submit the request and wait for our team to approve it!

Once approved, your server will automatically appear in the **ClutchHub** app for all users. 🚀
