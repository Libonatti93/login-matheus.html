# Área de Login

Este é um projeto simples de área de login, criado usando HTML, CSS e JavaScript. Ele serve como um exemplo básico de como criar uma interface de login, verificar credenciais e exibir mensagens de erro ou sucesso.

## Funcionalidades

- **Interface de Login**: Interface de usuário minimalista e amigável para o usuário inserir nome de usuário e senha.
- **Validação de Credenciais**: Verifica se o nome de usuário e a senha estão corretos (usando valores fixos de exemplo).
- **Mensagens de Erro**: Exibe mensagens de erro caso os campos estejam vazios ou as credenciais estejam incorretas.
- **Mensagem de Sucesso**: Exibe uma mensagem de sucesso quando o login é bem-sucedido.

## Tecnologias Utilizadas

- **HTML**: Estrutura da página e dos campos de entrada.
- **CSS**: Estilos para criar um layout centralizado e visual agradável.
- **JavaScript**: Lógica de validação do login e manipulação de eventos.

## Como Usar

1. **Clonar o repositório** ou baixe o arquivo `login.html` para o seu computador.
2. Abra o arquivo `login.html` em qualquer navegador web.
3. No formulário de login, insira o nome de usuário e senha como no exemplo abaixo:

   - **Usuário**: `usuario`
   - **Senha**: `senha123`

4. Clique no botão "Entrar".
   - Se as credenciais estiverem corretas, uma mensagem de sucesso será exibida.
   - Se as credenciais estiverem incorretas, uma mensagem de erro será exibida.

## Estrutura do Código

- **HTML**: Contém os campos de entrada para "Usuário" e "Senha", um botão de "Entrar" e uma área para exibir mensagens de erro.
- **CSS**: Aplica estilo ao formulário, tornando-o centralizado e com um design limpo.
- **JavaScript**: Função `login()` para validar a entrada do usuário e senha, com verificações simples de valores fixos para autenticação.

## Personalização

- **Modificar Credenciais**: Para mudar as credenciais, edite os valores na função `login()` no trecho de código JavaScript:
  ```javascript
  if (username === "novoUsuario" && password === "novaSenha") {
      alert("Login bem-sucedido!");
  }
