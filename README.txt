🔐 Sistema de Autenticação (Login & Register)

Aplicação web que implementa autenticação de usuários com funcionalidades de 👇

• Registro
• Login seguro
• Integração com Google OAuth desenvolvida com Node.js
• Express.js,
• PostgreSQL, 
• Passport.js.

O objetivo é fornecer uma base sólida para sistemas que exigem autenticação segura, escalável e com boa experiência de usuário.

------------------------------------------------------------------------------

 🚀 Tecnologias Utilizadas

• Node.js
• Express.js
• PostgreSQL
• EJS (template engine)
• Passport.js (LocalStrategy + Google OAuth 2.0)
• bcrypt (criptografia de senhas)
• dotenv (variáveis de ambiente)

------------------------------------------------------------------------------

⚙️ Funcionalidades

• ✅ Registro de novos usuários com senhas criptografadas
• ✅ Login com autenticação local segura
• ✅ Login com conta Google (OAuth 2.0)
• ✅ Armazenamento de segredos pessoais por usuário
• ✅ Visualização e atualização do segredo do usuário autenticado
• ✅ Sessões protegidas com `express-session` e Passport

------------------------------------------------------------------------------

▶️ Como rodar o projeto localmente

• Clone o repositório
git clone https://github.com/leandrobss1/Authentication-Login

• Entre na pasta
cd seu-repo

• Instale as dependências
npm install

• Crie um arquivo .env com as variáveis necessárias
touch .env
