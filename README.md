# Postman Collection for the Surparcel API

Contact us and request your business account to access the official Surparcel API documentation.

> **IMPORTANT:** postman is available as a web application (https://www.postman.com/) or a desktop application running on Windows, Mac etc. 

### Get Started

1. Após obter a sua conta empresarial no portal e estando logado no sistema, navegue ate o perfil de usuário e obtenha o client ID e client secret para seu aplicativo.
2. Import the FreeAgent collection

3. Fill in the environment variables for `client_id`
and `client_secret` from your app (which you created in step 1).

4. Generate your access and refresh tokens.

#### Common Gotchas
If your attempt to obtain an access token fails with the `"HTTP Basic: Access denied."` error, check your environment file and ensure the `client_id` and `client_secret` are entered correctly and don't contain any trailing whitespace/newline characters.

- Production Enviroment:
  - https://surparcel.com/api

- Stagging enviroment:
  - https://sur.gafit.com.br/api
