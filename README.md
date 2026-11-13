# 🤖 Simple Starter Bot

🇺🇸 **English** | 🇧🇷 **Português**

---

## 🇺🇸 English

A free, open-source Discord moderation bot built with **discord.js v14** and Slash Commands. Features role-based muting and essential moderation tools.

### ✨ Features
- `/setmuterole` — Select the role used to mute members.
- `/mute` — Mute a member using the configured mute role.
- `/unmute` — Unmute a member by removing the mute role.
- `/ban` — Ban a member with an optional reason.
- `/kick` — Kick a member with an optional reason.
- `/clear` — Bulk delete messages (1–100) from a channel.
- Automatic Slash Command registration on startup.

### 🚀 Getting Started
1. Clone or download this repository.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Rename `.env.example` to `.env` and add your bot token from the [Discord Developer Portal](https://discord.com):
   ```env
   DISCORD_TOKEN=your_bot_token_here
   ```
4. Start the bot:
   ```bash
   npm start
   ```
5. In your Discord server, run `/setmuterole` to choose which role will be applied when muting users.

### 🔐 Required Bot Permissions
Make sure the bot's role is positioned **above** the Mute role and target members' roles, and has:
- **Manage Roles**
- **Manage Messages**
- **Kick Members**
- **Ban Members**

### 🤝 Contributing
Pull Requests are welcome! Feel free to fork this repository, fix bugs, or add new commands.

### 📄 License
This project is licensed under the **MIT License**.

---

## 🇧🇷 Português

Um bot de moderação para Discord gratuito e open source, feito com **discord.js v14** e Slash Commands. Possui sistema de mute por cargo configurável e ferramentas essenciais de moderação.

### ✨ Funcionalidades
- `/setmuterole` — Seleciona o cargo usado para silenciar membros.
- `/mute` — Silencia um membro aplicando o cargo de mute configurado.
- `/unmute` — Remove o silenciamento retirando o cargo de mute.
- `/ban` — Bane um membro com motivo opcional.
- `/kick` — Expulsa um membro com motivo opcional.
- `/clear` — Apaga mensagens em massa (1 a 100) de um canal.
- Registro automático dos Slash Commands ao iniciar o bot.

### 🚀 Como Usar
1. Faça um clone ou baixe este repositório.
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Renomeie `.env.example` para `.env` e adicione o token do seu bot gerado no [Portal de Desenvolvedores do Discord](https://discord.com):
   ```env
   DISCORD_TOKEN=seu_token_aqui
   ```
4. Inicie o bot:
   ```bash
   npm start
   ```
5. No seu servidor do Discord, use `/setmuterole` para escolher qual cargo será aplicado ao mutar usuários.

### 🔐 Permissões Necessárias
Certifique-se de que o cargo do bot esteja posicionado **acima** do cargo de Mute e dos cargos dos membros alvo, e tenha:
- **Gerenciar Cargos** (`Manage Roles`)
- **Gerenciar Mensagens** (`Manage Messages`)
- **Expulsar Membros** (`Kick Members`)
- **Banir Membros** (`Ban Members`)

### 🤝 Como Contribuir
Pull Requests são muito bem-vindos! Sinta-se à vontade para fazer um fork deste repositório, corrigir bugs ou adicionar novos comandos.

### 📄 Licença
Este projeto está sob a **Licença MIT**.
