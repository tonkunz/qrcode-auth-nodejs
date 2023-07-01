### Entendendo a aplicação / Understanding the application

 - PT-BR: O autenticação é feita usando JWT e a lib bcrypt para encriptar este token;
   EN: The app uses JWT to sign and bycrypt to encrypt;

 - PT-BR: Quando os usuários registrarem-se, é criado um user record para cada um, e então quando eles se autenticam, é feito a checagem das credenciais enviadas e salvas;  
   EN: When users signup for the first time, we'll create a user record, and when they log in, we'll check the credentials against the saved user credentials.
  
### Documentação dos métodos da aplicação

 /register:
  - Collected data from users.
  - Verify the user's input.
  - Check to see if the user has already been registered.
  - Protect the user's password by encrypting it.
  - Create a user account in our database.
  - Finally, generate a JWT token that is signed.